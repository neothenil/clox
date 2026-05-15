cmake_minimum_required(VERSION 3.29)

project(clox C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

include_directories(src)
file(GLOB sources ${CMAKE_SOURCE_DIR}/src/*.c)
add_executable(clox ${sources})
