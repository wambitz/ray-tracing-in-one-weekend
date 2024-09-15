cmake_minimum_required(VERSION 3.16 FATAL_ERROR)

# Set C++ standard to C++17
set(CMAKE_CXX_STANDARD 17)

# Add compiler flags for debugging
set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -g")
set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -O0")

# Define the project name
project(RayTracing)

# Add subdirectories for each subproject
add_subdirectory(02_OutputAnImage)
