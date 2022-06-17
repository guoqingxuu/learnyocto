project(helloyocto C)
cmake_minimum_required(VERSION 2.6.3)
#add_subdirectory(src bin)
add_executable (heyc main.c)
install(TARGETS (heyc DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)

