# Minimum required version of CMake
cmake_minimum_required(VERSION 3.10)

# Project name
project(SocketExample)

# Define the source files
set(SOURCE_SERVER src/server/server.cc)
set(SOURCE_CLIENT src/client/client.cc)

# Build executable for a.cc
add_executable(server ${SOURCE_SERVER})

# Build executable for b.cc
add_executable(client ${SOURCE_CLIENT})
