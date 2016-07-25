cmake_minimum_required(VERSION 3.5)
project(ePass_test)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} ")

set(SOURCE_FILES pam_test.c pam_test.h SKFAPI.h skf_test.h test.c)
add_executable(ePass_test ${SOURCE_FILES})