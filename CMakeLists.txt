# Specify the minimum version for CMake
cmake_minimum_required(VERSION 3.10)

# Project's name
project(fixgz)

# Set the C++ standard
set(CMAKE_CXX_STANDARD 14)

# Add executable
add_executable(${PROJECT_NAME} main.c)
