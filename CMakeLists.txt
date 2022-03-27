cmake_minimum_required(VERSION 3.5)

project(Rte LANGUAGES C)

add_library(Rte Rte.c)

target_include_directories(Rte PRIVATE ../BSW)
target_link_libraries(Rte PRIVATE Bsw)
