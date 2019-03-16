cmake_minimum_required(VERSION 3.13)

project(Plumber)

set(VERSION "0.1.0")

option(BUILD_TESTS "Build test" On)

add_subdirectory(src)

if(BUILD_TESTS)
  add_subdirectory(test)
endif()