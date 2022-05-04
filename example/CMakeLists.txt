cmake_minimum_required(VERSION 3.14 FATAL_ERROR)

project(cc_stdio_example)

include(../cmake/cc_stdio.cmake)

important_message("hello, world")

message("no color")
message(STATUS "level == STATUS")
message(AUTHOR_WARNING "level == AUTHOR_WARNING")
message(WARNING "level == WARNING")
message(SEND_ERROR "level == SEND_ERROR")
message(FATAL_ERROR "level == FATAL_ERROR")

