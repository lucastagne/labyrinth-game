cmake_minimum_required(VERSION 3.16)
project(project C)

set(CMAKE_C_STANDARD 99)

add_executable(projet main.c game.c menu.h menu.c)
