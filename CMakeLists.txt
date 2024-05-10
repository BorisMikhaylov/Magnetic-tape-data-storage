cmake_minimum_required(VERSION 3.27)
project(YadroTesting)

set(CMAKE_CXX_STANDARD 20)

include(cmake/FindCatch.cmake)
include(cmake/TestSolution.cmake)

add_subdirectory(app)
add_subdirectory(test)
