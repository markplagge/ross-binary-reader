cmake_minimum_required(VERSION 2.8)
set(CMAKE_C_STANDARD 99)
project(RossBinReader)

set(src reader.c)

add_executable(ross-reader ${src})
