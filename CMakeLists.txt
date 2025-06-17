# Specify the minimum version of CMake required
cmake_minimum_required(VERSION 3.10)

# Define the project name and language
project(SimpleCMakeDemo CXX)

# Set the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add source files
set(SOURCES
    src/main.cpp
)

# Create an executable
add_executable(${PROJECT_NAME} ${SOURCES})