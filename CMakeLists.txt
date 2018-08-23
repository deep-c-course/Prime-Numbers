cmake_minimum_required(VERSION 2.6)
project(prime_numbers)

add_executable(prime_numbers main.c)

install(TARGETS prime_numbers RUNTIME DESTINATION bin)
