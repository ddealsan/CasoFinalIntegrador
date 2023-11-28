cmake_minimum_required(VERSION 3.10)
project(CasoFinalIntegrador)

set(CMAKE_CXX_STANDARD 14)

add_executable(Ejercicio1
        Ejercicio1/main.cpp
)


target_include_directories( Ejercicio1 PRIVATE ruta_al_directorio_que_contiene_json11_hpp)


target_sources( Ejercicio1 PRIVATE ${CMAKE_SOURCE_DIR}/ruta/b/main.cpp)