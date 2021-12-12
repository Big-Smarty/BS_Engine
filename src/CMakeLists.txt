#/src/CMakeLists.txt

cmake_minimum_required(VERSION 3.20)

add_subdirectory(context)
add_subdirectory(renderstage)

add_executable(bs_engine engine.cpp)
target_link_libraries(bs_engine bs_context)
