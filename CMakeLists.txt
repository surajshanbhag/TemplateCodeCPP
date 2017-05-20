cmake_minimum_required (VERSION 2.6)
project(TemplateCode)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
include_directories("${PROJECT_SOURCE_DIR}/include")
file(GLOB src
    "src/*.cc"
    )

add_executable(TemplateCode ${src})
#add_executable(TemplateCode src/main.cc)
