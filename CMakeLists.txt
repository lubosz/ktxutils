cmake_minimum_required (VERSION 2.8.11)

project (ktxutils)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_SOURCE_DIR}/bin/")

set(GLFW3_LIBRARY glfw)

add_subdirectory (src)
