cmake_minimum_required(VERSION 3.25)
project(ShouldBeStandard)

set(CMAKE_CXX_STANDARD 23)

add_library(SBS INTERFACE)
target_include_directories(SBS INTERFACE "${CMAKE_CURRENT_LIST_DIR}/include")

add_subdirectory(tests)