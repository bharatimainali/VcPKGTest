cmake_minimum_required(VERSION 3.10)

project(MyTestProject)

find_package(spdlog REQUIRED)

add_executable(my_test_project main.cpp)

target_link_libraries(my_test_project PRIVATE spdlog::spdlog)