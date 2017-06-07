cmake_minimum_required(VERSION 3.6)
project(untitled9)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp hex_print.h hex_print.cpp bin_print.h bin_print.cpp)
add_executable(untitled9 ${SOURCE_FILES})