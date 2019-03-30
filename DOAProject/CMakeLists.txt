cmake_minimum_required(VERSION 3.8)
project(DOAProject)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c)
add_executable(DOAProject ${SOURCE_FILES} index.c list.c query.c heap.c)