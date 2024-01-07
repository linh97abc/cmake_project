cmake_minimum_required(VERSION 3.21)

project(test)

add_subdirectory(test1)
add_subdirectory(test2)

add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/../src src)