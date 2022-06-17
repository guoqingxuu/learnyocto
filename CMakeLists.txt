project(helloyocto C)
cmake_minimum_required(VERSION 2.6.3)
add_subdirectory(src bin)
#add_executable (heyc main.c)

#set(CMAKE_INSTALL_PREFIX ./bin/)
MESSAGE("this is" ${CMAKE_INSTALL_PREFIX})

