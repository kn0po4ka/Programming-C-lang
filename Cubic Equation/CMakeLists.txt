cmake_minimum_required(VERSION 3.17)
project(right3_3 C)

set(CMAKE_C_STANDARD 99)

add_executable(right3_3 main.c)
target_link_libraries(right3_3 m)