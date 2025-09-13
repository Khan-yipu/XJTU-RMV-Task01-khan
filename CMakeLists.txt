cmake_minimum_required(VERSION 3.11)

project(hello_rmv)

include_directories(./includes)

add_executable(hello_dxrmv ./src/cmake_learn.cpp ./tools/hello.cpp)
