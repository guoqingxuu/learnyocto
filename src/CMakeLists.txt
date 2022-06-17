
add_executable(xht main.c)
MESSAGE("proj dir is" ${PROJECT_BINARY_DIR})
#MESSAGE("little proj dir is" ${project_binary_dir})#project_binary_dir not use lower-case
SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin22)
install(TARGETS xht DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)

