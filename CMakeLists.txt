cmake_minimum_required(VERSION 3.10)

project(TC1030_Tarea2)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

file(GLOB SOURCES "src/*.cpp")

add_executable(tarea2 ${SOURCES})
