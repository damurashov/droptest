cmake_minimum_required(VERSION 3.12)
project(EXECUTABLE_NAME_STUB)
include_directories(".")
file(GLOB SOURCES "*.cpp")
set(EXECUTABLE_NAME EXECUTABLE_NAME_STUB)
add_executable(${EXECUTABLE_NAME} ${SOURCES})
set_property(TARGET ${EXECUTABLE_NAME} PROPERTY CXX_STANDARD 11)
add_compile_options(${EXECUTABLE_NAME} PUBLIC "-ggdb")
