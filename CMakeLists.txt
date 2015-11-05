cmake_minimum_required(VERSION 3.3)
project(learn_cpp)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp "Chapter 0/Chapter 0.1/main.cpp" "Chapter 0/Chapter 0.1/main.h")
add_executable(learn_cpp ${SOURCE_FILES})