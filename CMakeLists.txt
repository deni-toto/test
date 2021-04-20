cmake_minimum_required(VERSION 2.8)
project(TestProject)

string(TIMESTAMP t "%H:%M:%S")
message(STATUS "time: ${TIME}")

add_executable(${PROJECT_NAME} main.cpp)