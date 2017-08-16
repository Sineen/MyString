cmake_minimum_required(VERSION 3.6)
project(MyString)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")

set(SOURCE_FILES MyString.c)
add_executable(MyString ${SOURCE_FILES})