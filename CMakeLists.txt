cmake_minimum_required(VERSION 3.22)
project(LifeManagementSystem)

set(CMAKE_CXX_STANDARD 14)

add_executable(LifeManagementSystem main.cpp src/Layers/Operation.cpp src/Layers/Operation.h)
