# CMakeList.txt : CMake project for RTOneWeekend, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("RTOneWeekend")

# Add source to this project's executable.
add_executable (RTOneWeekend src/main.cc src/vec3.h src/color.h src/ray.h)

# TODO: Add tests and install targets if needed.
