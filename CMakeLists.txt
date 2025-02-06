cmake_minimum_required (VERSION 3.30)
project (cmake_template)

set (CMAKE_C_STANDARD 23)

file(GLOB src_files "src/*.c")

add_executable(cmake_template ${src_files})

target_link_libraries(cmake_template)