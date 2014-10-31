cmake_minimum_required(VERSION 2.8.4)
project(bjarne_says_I_must_learn_c)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(bjarne_says_I_must_learn_c ${SOURCE_FILES})