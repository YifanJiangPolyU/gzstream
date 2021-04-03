cmake_minimum_required(VERSION 3.5)

project(gzstream)

add_library(${PROJECT_NAME}_lib
    gzstream.h
    gzstream.C
)

target_link_libraries(${PROJECT_NAME}_lib z)
