project(CPPMinimal)
cmake_minimum_required(VERSION 3.5)

set(PROJECT_SOURCE_DIR     ${CMAKE_SOURCE_DIR}/src)
set(CMAKE_BINARY_DIR       ${CMAKE_SOURCE_DIR}/bin)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR})
set(LIBRARY_OUTPUT_PATH    ${CMAKE_BINARY_DIR})

# Enable C++ 14
add_compile_options(-std=c++14)

# Do not remove the following auto-generated signatures

# Auto-generated. Do not edit. All changes will be undone
set(SourceFiles
    ${PROJECT_SOURCE_DIR}/main.cpp
   )
# Auto-generated end


add_executable(CPPMinimal ${SourceFiles})
