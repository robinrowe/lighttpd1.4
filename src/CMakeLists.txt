# src/CMakeLists.txt
# Created by Robin Rowe 2024-09-11
# License Open Source BSD License

set (MODULE_NAME src)
message("Configuring ${MODULE_NAME} 163 source file(s)")
file(STRINGS sources.cmake SOURCES)
add_executable(${MODULE_NAME} ${SOURCES})
