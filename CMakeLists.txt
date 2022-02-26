cmake_minimum_required(VERSION 3.10)

project(unit_testing)

enable_testing()

add_executable(hello hello.cpp)
add_executable(helloTest helloTest.cpp)
add_executable(helloTest_01 helloTest_01.cpp)
add_executable(helloTest_02 helloTest_02.cpp)
add_executable(helloTest_03 helloTest_03.cpp)

add_test(NAME helloTest COMMAND helloTest)
add_test(NAME helloTest_01 COMMAND helloTest_01)
add_test(NAME helloTest_02 COMMAND helloTest_02)
add_test(NAME helloTest_03 COMMAND helloTest_03)
