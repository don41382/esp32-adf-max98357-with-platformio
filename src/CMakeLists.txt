# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

## OLD
FILE(GLOB_RECURSE app_sources ${CMAKE_SOURCE_DIR}/src/*.*)
set(COMPONENT_SRCS adf_music.mp3)
idf_component_register(SRCS ${app_sources})

# set(COMPONENT_SRCS "main.c")
# set(COMPONENT_ADD_INCLUDEDIRS .)
# register_component()
