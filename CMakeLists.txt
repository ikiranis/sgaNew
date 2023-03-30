cmake_minimum_required(VERSION 3.24)
project(sgaNew C)

set(CMAKE_C_STANDARD 99)

add_executable(sgaNew main.c)

target_link_libraries(sgaNew m)


