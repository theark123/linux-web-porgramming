cmake_minimum_required(VERSION 3.25)
project(echo C)

set(CMAKE_C_STANDARD 11)

add_executable(server server.c)
add_executable(client client.c)