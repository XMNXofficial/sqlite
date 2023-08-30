cmake_minimum_required(VERSION 3.5)

project(sqlite CXX C)

add_library(sqlite
"include/sqlite3ext.h"
"include/sqlite3.h"
"lib/sqlite3.c"
)
