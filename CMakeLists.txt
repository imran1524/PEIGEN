include_directories("/usr/local/include" "/usr/local/opt/llvm/include")
link_directories("/usr/local/lib" "/usr/local/opt/llvm/lib")

cmake_minimum_required(VERSION 3.23)
project(PEIGEN-master)

set(CMAKE_CXX_STANDARD 17)

add_executable(PEIGEN-master main.cpp)
