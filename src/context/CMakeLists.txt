#/src/context/CMakeLists.txt

cmake_minimum_required(VERSION 3.20)
project(bs_context)

add_library(bs_context window/window.cpp instance/instance.cpp device/device.cpp swapchain/swapchain.cpp)
