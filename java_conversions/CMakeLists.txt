cmake_minimum_required(VERSION 3.8)

project(project_name)
set(TARGET project_name)

set(CMAKE_C_STANDARD   99)
set(CMAKE_CXX_STANDARD 20)

set(SOURCE_DIR "src")
set(SOURCES
    ${SOURCE_DIR}/Main.cpp
)

add_executable(${TARGET} ${SOURCES})
