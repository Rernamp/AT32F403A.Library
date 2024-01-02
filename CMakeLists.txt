cmake_minimum_required(VERSION 3.16)

add_library(AT32F403A.Library INTERFACE)
target_include_directories(AT32F403A.Library INTERFACE "Src")
add_subdirectory(Src)
