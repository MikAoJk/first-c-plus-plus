cmake_minimum_required(VERSION 3.25) # CMake version check
project(first-cpp) # Create project "first-cpp"

set(CMAKE_CXX_STANDARD 23)  # Enable c++23 standard

# Add main.cpp file of project root directory as source file
set(SOURCE_FILES main.cpp)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(first-cpp ${SOURCE_FILES})
