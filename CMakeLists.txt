cmake_minimum_required(VERSION 3.24)
project(repomolde C)

set(CMAKE_C_STANDARD 11)

add_executable(repomolde main.c helper.c helper.h)
