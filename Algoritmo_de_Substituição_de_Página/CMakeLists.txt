cmake_minimum_required(VERSION 3.10)
project(Algoritmo_de_Substitui��o_de_P�gina)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)
include_directories(Debug)
include_directories(Release)

add_executable(Algoritmo_de_Substitui��o_de_P�gina
        Debug/Algoritmo_de_Substitui��o_de_P�gina.pch
        Release/Algoritmo_de_Substitui��o_de_P�gina.pch
        Algoritmo_de_Substitui��o_de_P�gina.cpp
        stdafx.cpp
        stdafx.h
        targetver.h)
