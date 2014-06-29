#Specify the version being used as well as the language
cmake_minimum_required(VERSION 2.6)
#Name the project
project(fibonacci)

#Sends the -std=c99 flag to the gcc compiler
add_definitions(-std=c99)
#Tells CMake to fib.c and name it fibonacci
add_executable(fibonacci fib.c)
