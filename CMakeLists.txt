cmake_minimum_required(VERSION 3.10)

# Project settings
project(EncoderApp VERSION 1.0 LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

# Executable
file(GLOB SOURCES "src/*.cc")
add_executable(EncoderApp ${SOURCES})
