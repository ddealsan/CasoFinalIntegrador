cmake_minimum_required(VERSION 3.10)
project("CasoFinalIntegrador2")

set(CMAKE_CXX_STANDARD 14)

add_executable(Ejercicio
        Ejercicio/main.cpp)


target_include_directories(Ejercicio PRIVATE ${CMAKE_SOURCE_DIR}/ruta/a/json11.hpp)
target_include_directories(Ejercicio PRIVATE ${CMAKE_SOURCE_DIR}/ruta/a/jsonlib.hpp)

target_sources(Ejercicio PRIVATE ${CMAKE_SOURCE_DIR}/ruta/b/main.cpp)