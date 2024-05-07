cmake_minimum_required(VERSION 3.28)
project(Snake)

set(CMAKE_CXX_STANDARD 20)

set(CMAKE_CXX_FLAGS " -static -static-libgcc -static-libstdc++ -mwindows")

add_executable(Snake Snake.cpp)
