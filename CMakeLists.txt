cmake_minimum_required(VERSION 3.22)
project(nekhbet C CXX)

set(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 20)

add_library(nekhbet SHARED)

include(${CMAKE_CURRENT_LIST_DIR}/nekhbet/CMakeLists.txt)
