cmake_minimum_required(VERSION 3.18)
project(etcpack)

set(CMAKE_CXX_STANDARD 11)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_executable(etcpack
        etcdec.cxx
        etcpack.cxx
        image.cxx
        )