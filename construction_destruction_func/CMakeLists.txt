cmake_minimum_required(VERSION 3.20.0)
project(construction_destruction_func)
set(CMAKE_CXX_STANDARD 11)

include_directories(${PROJECT_SOURCE_DIR}/inc)
# 变量设置
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/bin)
aux_source_directory(${CMAKE_SOURCE_DIR}/src SRC_LIST)

add_executable(construction_destruction_func ${SRC_LIST})