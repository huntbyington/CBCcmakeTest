cmake_minimum_required(VERSION 3.10)
project(Problem1 C)

include_directories(. ./harp ./lib)
add_executable(perform main.c ./harp/harp.c ./lib/strings.c)