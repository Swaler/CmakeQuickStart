cmake_minimum_required(VERSION 3.29)

project("YandexPracticum" VERSION 1.0.0 LANGUAGES CXX)

add_executable(${PROJECT_NAME})

target_compile_features(${PROJECT_NAME} PUBLIC cxx_std_20)

add_subdirectory(src)
