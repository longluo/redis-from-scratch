cmake_minimum_required(VERSION 3.16)

project(redis)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)


# Add executable for server
add_executable(avl avl.cpp test_avl.cpp)

