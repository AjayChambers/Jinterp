cmake_minimum_required(VERSION 3.20)

project(
    Jinterp
    VERSION 0.1.0
    DESCRIPTION "JSON Interpreter"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

include(cmake/CompilerWarnings.cmake OPTIONAL)

add_subdirectory(source)
add_subdirectory(tests)
