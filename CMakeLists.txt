cmake_minimum_required(VERSION 3.8)
project(lshell)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c lshell.c lshell.h prefix.c)
add_executable(lshell ${SOURCE_FILES})