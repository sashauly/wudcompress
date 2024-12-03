cmake_minimum_required(VERSION 3.10)
project(wudcompress VERSION 1.0 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME}
    main.cpp
    wud.cpp
)

target_include_directories(${PROJECT_NAME} PRIVATE ./)
