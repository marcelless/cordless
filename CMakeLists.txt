cmake_minimum_required(VERSION 3.18)
project(cordless)

add_executable(cordless main.cpp)

set_target_properties(cordless PROPERTIES CXX_STANDARD 17 CXX_EXTENSIONS OFF)