cmake_minimum_required(VERSION 3.10)
project(timespan)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(timespan
        main.cpp
        timespan.cpp
        timespan.h)