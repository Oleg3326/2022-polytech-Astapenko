cmake_minimum_required(VERSION 3.22 FATAL_ERROR)

project(hello)

set(CMAKE_CXX_STANDARD 17)

set(SOURCES main.cpp func.h func.cpp)

add_executable(${PROJECT_NAME} ${SOURCES})