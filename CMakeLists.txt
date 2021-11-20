cmake_minimum_required(VERSION 3.20)
project(md5)

set(CMAKE_CXX_STANDARD 17)

add_executable(md5 main.cpp MD5.h MD5.cpp)
