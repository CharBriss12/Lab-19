cmake_minimum_required(VERSION 3.24)
project(lab_19 C)

set(CMAKE_C_STANDARD 11)

add_executable(lab_19 main.c Libs/array/array.c Libs/array/array.h Libs/set_bits/set_bits.c Libs/set_bits/set_bits.h Libs/set_ordered/set_ordered.c Libs/set_ordered/set_ordered.h Libs/set_unordered/set_unordered.c Libs/set_unordered/set_unordered.h Libs/vector/vector.c Libs/vector/vector.h Libs/vectors_void/Vector_void.c Libs/vectors_void/vector_void.h)
