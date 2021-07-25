cmake_minimum_required(VERSION 3.10)

project(hello)

add_executable(hello hello.cpp)

enable_testing()
add_test(NAME hello_world COMMAND hello)
add_test(NAME hello_user COMMAND hello user)
