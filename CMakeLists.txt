cmake_minimum_required(VERSION 3.16)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_CXX_STANDARD 20)

project(imgui_glfw)

add_executable(${CMAKE_PROJECT_NAME}
    src/main.cpp
)
