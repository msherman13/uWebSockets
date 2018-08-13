cmake_minimum_required(VERSION 3.9)

project(uwebsockets)
add_subdirectory(src)

find_package(OpenSSL REQUIRED)
