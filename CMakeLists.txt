cmake_minimum_required(VERSION 3.8)
project(tc_shared)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES print.cpp print.h)
add_library(tc_shared SHARED ${SOURCE_FILES})