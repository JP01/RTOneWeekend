# CMakeList.txt : CMake project for RTOneWeekend, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("RTOneWeekend")

# Add source to this project's executable.
add_executable (RTOneWeekend 
	src/camera.h
	src/color.h 
	src/main.cc 
	src/ray.h 
	src/rtweekend.h
	src/vec3.h 

	src/hittables/hittable.h 
	src/hittables/hittable_list.h
	src/hittables/sphere.h
 "src/material.h")