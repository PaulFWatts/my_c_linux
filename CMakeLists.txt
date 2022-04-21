cmake_minimum_required(VERSION 3.22)
project(my_c_linux C)

set(CMAKE_C_STANDARD 11)

include_directories(simple_makefile_tutorial/include)

add_executable(my_c_linux
        simple_makefile_tutorial/include/hellomake.h
        simple_makefile_tutorial/src/hellofunc.c
        simple_makefile_tutorial/src/hellomake.c)
