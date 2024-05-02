cmake_minimum_required(VERSION 3.27)
project(OOP_3_3D)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(Google_test)

add_executable(OOP_3_3D main.cpp
        Car.cpp
        Bus.cpp
        BusC.cpp)
