cmake_minimum_required(VERSION 3.10...4.4)

# Имя проекта и язык программирования
project(MyProject LANGUAGES CXX)


# Установка стандарта C++ (например, C++17 или C++20)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Создание исполняемого файла (имя программы и список исходных файлов)
add_executable(repository_test\lecture4\main.cpp)
