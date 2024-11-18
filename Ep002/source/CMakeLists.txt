cmake_minimum_required(VERSION 3.5)

project(HelloCmake
        VERSION 0.0.1
        DESCRIPTION "Hello World App"
        LANGUAGES CXX)

add_executable(HelloCMake main.cpp)
target_compile_features(HelloCMake PRIVATE cxx_std_20)