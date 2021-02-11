cmake_minimum_required (VERSION 3.7.1)
project (query)

include_directories(Eigen3)
include_directories(igl)
include_directories(include)
file(GLOB SOURCES "src/*.cpp")

add_executable(query ${SOURCES})