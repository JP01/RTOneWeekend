# Add source to this project's executable.
add_executable (RTOneWeekend 
	"camera.h"
	"color.h" 
	"main.cc"
	"material.h"
	"ray.h" 
	"rtweekend.h"
	"vec3.h" 

	"hittables/hittable.h "
	"hittables/hittable_list.h"
	"hittables/sphere.h"
)