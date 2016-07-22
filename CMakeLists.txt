cmake_minimum_required(VERSION 3.5)
project(cpp)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp 1.1.cpp 1.2.cpp 1.3.cpp 1.4.cpp 1.5.cpp)
add_executable(Test ${SOURCE_FILES})