cmake_minimum_required(VERSION 3.0)

project(anyledger-wallet-helpers)
include_directories(..)

file(GLOB SOURCES "*.c")

add_library(helpers STATIC ${SOURCES})
