cmake_minimum_required(VERSION 3.3)
project(thompson)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES thompson.c)
add_executable(thompson ${SOURCE_FILES})