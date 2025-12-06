cmake_minimum_required(VERSION 3.31)
project(KakSdelatKG)

set(CMAKE_CXX_STANDARD 20)

add_executable(KakSdelatKG main.cpp
        tgaimage.cpp
        tgaimage.h
        math.h
        model.cpp
        model.h)
