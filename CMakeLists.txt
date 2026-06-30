cmake_minimum_required(VERSION 3.31)
project(CPP-PLANER VERSION 1.0 LANGUAGES CXX)

set(SOURCES
    src/main.cpp

)
add_executable(CPP-PLANER main.cpp)
target_include_directories(CPP-PLANER PUBLIC include)