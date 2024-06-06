cmake_minimum_required(VERSION 3.26)
project(lab_15 C)

set(CMAKE_C_STANDARD 11)

add_executable(lab_15 main.c
        libraris/struct_matrix/matrix.c
        libraris/struct_matrix/matrix.h)
