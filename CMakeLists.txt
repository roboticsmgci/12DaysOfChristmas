cmake_minimum_required(VERSION 3.21)
project(12DaysOfChristmas)

set(CMAKE_CXX_STANDARD 14)

include_directories(days)

add_executable(12DaysOfChristmas
        days/day01.cpp
        days/day01.h
        days/day02.cpp
        days/day02.h
        days/day03.cpp
        days/day03.h
        days/day04.cpp
        days/day04.h
        days/day05.cpp
        days/day05.h
        days/day06.cpp
        days/day06.h
        days/day07.cpp
        days/day07.h
        days/day08.cpp
        days/day08.h
        days/day09.cpp
        days/day09.h
        days/day10.cpp
        days/day10.h
        days/day11.cpp
        days/day11.h
        days/day12.cpp
        days/day12.h
        days/intro_line.cpp
        days/intro_line.h
        main.cpp)
