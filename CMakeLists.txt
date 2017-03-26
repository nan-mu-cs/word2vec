cmake_minimum_required(VERSION 3.6)
project(embedding)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        word2vec_kernels.cc
        word2vec_ops.cc)

add_executable(embedding ${SOURCE_FILES})