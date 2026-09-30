cmake_minimum_required(VERSION 3.10)
project(Problem2 C)

include_directories(. ../include)
add_executable(perform main.c ../include/action.c ../include/message.c)