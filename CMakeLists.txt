cmake_minimum_required(VERSION 3.13)
project(seats)

set(CMAKE_CXX_STANDARD 11)

add_executable(seats test_part_c.cpp seat.cpp seat.h)