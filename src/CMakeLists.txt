cmake_minimum_required(VERSION 3.2)

add_library(libutf libutf.c)

target_include_directories(libutf PUBLIC ${LIBUTF_INCLUDE_DIRECTORY})