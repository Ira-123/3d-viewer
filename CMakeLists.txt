cmake_minimum_required(VERSION 3.10)
project(My3DViewer)

set(CMAKE_CXX_STANDARD 17)

find_package(glm CONFIG REQUIRED)
find_package(glfw3 CONFIG REQUIRED)

add_executable(My3DViewer main.cpp)

target_link_libraries(My3DViewer PRIVATE glfw)
