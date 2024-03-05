cmake_minimum_required(VERSION 3.14...3.22)

project (template)

include(cmake/CPM.cmake)

file(GLOB SOURCES src/*/**.cpp src/*.cpp)

add_executable(template ${SOURCES})
