cmake_minimum_required(VERSION 3.15..3.30)
project(Homie VERSION 1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_FLAGS "-Wall")

set(PROJECT-SOURCES
        main.cpp
)

add_executable(Homie ${PROJECT-SOURCES})
