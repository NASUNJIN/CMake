# cmake version
cmake_minimum_required(VERSION 3.25)

# project name : hello_world
# project version : 0.1.0
project(hello_world VERSION 0.1.0)

# C++11
set(CMAKE_CXX_STANDARD 11)

# main이라는 이름의 실행 파일을 만들고, main.cpp라는 소스 파일을 사용하여 빌드
add_executable(main main.cpp)