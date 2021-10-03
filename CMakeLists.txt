cmake_minimum_required(VERSION 3.10)
project(avir LANGUAGES CXX)
add_library(avir INTERFACE)
target_include_directories(avir INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
