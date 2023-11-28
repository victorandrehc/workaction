cmake_minimum_required(VERSION 3.25)
project(workaction)

set(CMAKE_CXX_STANDARD 20)

find_package(Qt6 6.5 REQUIRED COMPONENTS Quick)
qt_standard_project_setup(REQUIRES 6.5)

add_executable(workaction main.cpp)
