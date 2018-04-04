cmake_minimum_required(VERSION 3.10)
project(Hello_World)

set(CMAKE_CXX_STANDARD 11)

add_executable(Hello_World main.cpp cmake-build-debug/my_lib.h unittest.cpp)