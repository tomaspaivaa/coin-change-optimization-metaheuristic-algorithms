cmake_minimum_required(VERSION 3.27)
project(trepaColinas)

set(CMAKE_C_STANDARD 17)

add_executable(trepaColinas main.c
        utils.c
        utils.h
        algorithm.c
        algorithm.h)
