cmake_minimum_required(VERSION 2.6)
project(morphology)
find_package(OpenCV REQUIRED)
add_executable(morphology morphology.cpp)
target_link_libraries(morphology ${OpenCV_LIBS})
