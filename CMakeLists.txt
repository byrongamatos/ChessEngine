cmake_minimum_required(VERSION 2.8.4)
project(Chess_Engine)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")

set(SOURCE_FILES vice.c)
add_executable(Chess_Engine ${SOURCE_FILES})