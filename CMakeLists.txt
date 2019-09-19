cmake_minimum_required (VERSION 2.6)

project(SOIL)

set(CMAKE_C_FLAGS "-x objective-c")

file(GLOB SOIL_SOURCES src/*.c)
file(GLOB SOIL_HEADERS src/*.h)

add_library(SOIL ${SOIL_SOURCES} ${SOIL_HEADERS})
