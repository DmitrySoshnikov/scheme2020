cmake_minimum_required(VERSION 3.15)
project(Scheme2020)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)


include_directories(include)
add_subdirectory(lib)
add_subdirectory(external)
add_subdirectory(unittests)
