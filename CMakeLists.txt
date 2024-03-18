cmake_minimum_required(VERSION 3.27)
project(Bil142_3)

set(CMAKE_CXX_STANDARD 23)

set(SOURCES
        src/main.cpp
        src/GemiSecici.cpp
        src/Oyun.cpp
        src/Eventler.cpp
)

include_directories(inc)

add_executable(Bil142_3 ${SOURCES})
