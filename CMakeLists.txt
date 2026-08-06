cmake_minimum_required(VERSION 3.10)

project(short_types)

set(CMAKE_C_STANDARD 23)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(short_types
    src/main.c
)

include_directories(include)