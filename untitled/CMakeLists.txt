cmake_minimum_required(VERSION 3.20)
project(untitled)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled main.cpp Dialog.cpp Dialog.h)

include_directories("/home/danila/1.2lab/lib")
target_link_libraries(untitled "cmake-build-debug/liblib.a")
