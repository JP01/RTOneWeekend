## Ray Tracing in One Weekend
Learning to implement a ray tracer by following along with
[_Ray Tracing in One Weekend_](https://raytracing.github.io/books/RayTracingInOneWeekend.html)

I won't be doing this in one weekend but over a couple of weeks/months when I get time.


# Examples
I started taking screen shot examples as I went once I got about half way through.
I started tracking render times in Debug builds when I added the camera in #3.

### 1. Creating a metallic material
<img src="output_images/RTOW_firstmetal.png" width=400 height=225/>

### 2. Creating a dielectric material - eg: a glass ball
<img src="output_images/RTOW_dielectric.png" width=400 height=225/>

## 3. Added positionable camera with controllable FOV 
Render Time: ~9.8s with no optimizations

<img src="output_images/RTOW_positioned_camera.png" width=400 height=225/>

## 4. Added defocus blur with controllable aperture size
Render Time: ~12.2s with no optimizations

<img src="output_images/RTOW_defocus_blur.png" width=400 height=225/>


## 5. Rendered the final image from the book
Render Time: ~415.3s (6m 55s) with no optimizations

<img src="output_images/RTOW_final_render.png" width=400 height=225/>


# Optimization

The final image render was pretty slow for such low resolution. Maybe we can speed it up!

## Standard MSVC Release optimization
Visual Studio can create a 'release' build which provides some standard optimizations.
This brought the final image render time to around ~50s.

## Other optimizations
There are other optimizations we can do. I'll update as I work my way through.

