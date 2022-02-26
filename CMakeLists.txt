cmake_minimum_required(VERSION 3.10)

project(unit_testing)

enable_testing()

add_executable(hello hello.cpp)
add_executable(helloTest helloTest.cpp)

add_test(NAME helloTest COMMAND helloTest)
