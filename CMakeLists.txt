# Establece la versión mínima requerida de CMake para este proyecto.
cmake_minimum_required(VERSION 3.15)
project(ProjectName)

# Especifica el estándar de C++ a utilizar.
set(CMAKE_CXX_STANDARD 17)

add_executable(Inventario src/main.cpp src/main.cpp
        include/CSVManager.h
        src/InventoryManager.cpp
        include/InventoryManager.h include/Article.h include/HashEntry.h include/HashMap.h include/HashTable.h)

# Enlaza las bibliotecas necesarias con tu ejecutable.
# target_link_libraries(Inventario nombre_de_la_biblioteca)
