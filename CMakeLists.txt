cmake_minimum_required(VERSION 3.29)
project(Testing C)

set(CMAKE_C_STANDARD 11)

add_executable(Testing
    main.c
        file1.c
        file1.h
        file2.c
        file2.h
        file3.c
        file3.h)
