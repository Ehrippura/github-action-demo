cmake_minimum_required(VERSION 3.16)

project(github-action-demo)
set(CMAKE_CXX_STANDARD 17)
file(GLOB SOURCES src/*.cpp)

add_executable(demo ${SOURCES})
