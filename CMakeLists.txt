# - Main CMake buildscript

# - Set CMake requirements then declare project
cmake_minimum_required(VERSION 3.3)
project(MPAGSCipher VERSION 0.1.0)

# - When Makefiles are generated, output all command lines by default
#   Do this to begin with so it's easy to see what compiler command/flags
#   are used. This can also be done by removing the 'set' command and
#   running make as 'make VERBOSE=1'.
set(CMAKE_VERBOSE_MAKEFILE ON)

# - Build the command line program
add_executable(mpags-cipher mpags-cipher.cpp)

