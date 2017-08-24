cmake_minimum_required(VERSION 3.8)
project(kvmsample)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        main.c
        test.S)

add_executable(kvmsample ${SOURCE_FILES})