cmake_minimum_required(VERSION 3.21)
project(TIC_TAC_TOE)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(TIC_TAC_TOE
        play.cpp
        play.hpp
        ttt.cpp)
