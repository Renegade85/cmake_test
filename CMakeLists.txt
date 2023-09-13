cmake_minimum_required (VERSION 3.16)

message(STATUS "default install: ${CMAKE_INSTALL_PREFIX}")

set (THIRDPARTY ON CACHE STRING "" FORCE)
set (BUILD_SHARED_LIBS OFF CACHE STRING "" FORCE)


add_subdirectory(3rdparty/memory)
add_subdirectory(3rdparty/Fast-DDS)


