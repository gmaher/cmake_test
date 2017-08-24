cmake_minimum_required (VERSION 3.0)
project (cmake_test)

add_subdirectory(submodule_1)

add_executable(main main.cpp)
target_link_libraries(main MY_MATH)
