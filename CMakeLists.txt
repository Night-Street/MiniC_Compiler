cmake_minimum_required(VERSION 3.20)
project(Mini_C)

set(CMAKE_CXX_STANDARD 14)

add_executable(Mini_C main.cpp scanner.h parser.h object_code_generator.h quadruples.h symbol_table.h "machine-independent optimizer.h")
