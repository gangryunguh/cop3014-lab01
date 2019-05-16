cmake_minimum_required(VERSION 3.08)
project(cop3014_lab01)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES firstprogram.cpp logicprob.cpp runprob.cpp semiprob.cpp)

add_executable(firstprogram.exe firstprogram.cpp)
add_executable(logicprob.exe logicprob.cpp)
add_executable(runprob.exe runprob.cpp)
add_executable(semiprob.exe semiprob.cpp)
