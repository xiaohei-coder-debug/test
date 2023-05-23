cmake_minimum_required(VERSION 3.0)
#SET(CMAKE_CXX_COMPILER "g++")
project(MY)
aux_source_directory(./src dir_src)
add_executable(my_cmake ${dir_src})
target_link_libraries(my_cmake m pthread)



