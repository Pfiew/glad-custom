cmake_minimum_required(VERSION 3.20)
project(glad VERSION 1.0)

add_library(glad)
target_sources(glad PRIVATE "sources/glad.c")
target_include_directories(glad PUBLIC "include")
set_property(TARGET glad PROPERTY C_STANDARD 99)
