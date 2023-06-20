cmake_minimum_required(VERSION 3.13)
project(taskset C)

set(CMAKE_C_STANDARD 11)

SET(CMAKE_C_COMPILER "aarch64-linux-gnu-gcc")

ADD_COMPILE_OPTIONS(-D_GNU_SOURCE)

add_executable(taskset taskset.c)