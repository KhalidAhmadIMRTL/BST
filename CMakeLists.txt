cmake_minimum_required(VERSION 3.12)
project(BST)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(BST
        BST312.h
        main.cpp
        test.txt BST312.cpp)
