cmake_minimum_required(VERSION 3.15) 

set(PROJECT_NAME S2-L9)
project("${PROJECT_NAME}")


set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

include_directories("/")

add_executable("${PROJECT_NAME}" 2sem.laba11.cpp inc/cPlusPlus
											inc/generateCode
											inc/java
											inc/php
											inc/someFunctions)
