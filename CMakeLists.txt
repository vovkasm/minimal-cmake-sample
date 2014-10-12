cmake_minimum_required(VERSION 3.0)
project(HelloWorld)

set(HelloWorld_SOURCES main.cpp)

source_group(Sources ${HelloWorld_SOURCES})

add_executable(hello ${HelloWorld_SOURCES})
