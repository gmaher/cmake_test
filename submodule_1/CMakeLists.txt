cmake_minimum_required (VERSION 3.0)
project (mymath)

#add_library(MY_MATH SHARED mymath.cpp include/mymath.h)
add_library(MY_MATH STATIC mymath.cpp include/mymath.h)
target_include_directories(MY_MATH PUBLIC include)
