cmake_minimum_required(VERSION 3.10)
project(SimpleList)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add source files
add_executable(SimpleList src/main.cpp)

# Include directories
target_include_directories(SimpleList PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)
