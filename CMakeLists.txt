cmake_minimum_required(VERSION 3.16)
project(main LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

find_package(opencv REQUIRED)

add_executable(a main.cpp)
target_link_libraries(a
 PRIVATE
 opencv_core
 opencv_objdetect
 opencv_video
 opencv_videoio
 opencv_highgui)