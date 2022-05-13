cmake_minimum_required(VERSION 3.22)
project(mario)
find_package(SFML 2.5 COMPONENTS graphics REQUIRED)
set(CMAKE_CXX_STANDARD 17)

add_executable(mario main.cpp)
target_link_libraries(mario sfml-graphics)
