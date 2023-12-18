cmake_minimum_required(VERSION 3.19)

project(include_problem CXX)

set(CMAKE_CXX_STANDARD 20)

add_executable(app main.cpp)
target_include_directories(app PRIVATE ".")

# target_precompile_headers(app
#     PRIVATE
#         "<atomic>"
# )
