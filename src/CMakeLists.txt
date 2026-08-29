cmake_minimum_required(VERSION 3.15)
project(Fun_Game VERSION 1.0 LANGUAGES C)

set(CMAKE_C_STANDARD 17)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(Test main.c)

target_compile_options(Test PRIVATE -Wall -Wextra -Werror)



