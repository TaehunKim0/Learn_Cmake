cmake_minimum_required(VERSION 3.22)

project(
  Hi
  LANGUAGES CXX
)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

file(GLOB_RECURSE SRC_FILES src/*.cpp)
add_executable(HelloCmake ${SRC_FILES})
target_compile_features(
  HelloCmake
  PRIVATE cxx_std_20
)
