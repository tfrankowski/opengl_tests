cmake_minimum_required(VERSION 3.16)

project(opengl_test)

set(CMAKE_CXX_STANDARD 17)

find_package(glfw3 REQUIRED)

add_subdirectory(glad)
add_subdirectory(test1)
add_subdirectory(test2)


