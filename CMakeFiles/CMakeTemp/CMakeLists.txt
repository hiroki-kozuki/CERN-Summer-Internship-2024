cmake_minimum_required(VERSION 3.20.2.0)
set(CMAKE_MODULE_PATH "/afs/cern.ch/work/k/kozuki/root_build/root_install/cmake/modules")
project(CMAKE_TRY_COMPILE C)
set(CMAKE_VERBOSE_MAKEFILE 1)
set(CMAKE_C_FLAGS "")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} ${COMPILE_DEFINITIONS}")
set(CMAKE_C_FLAGS_DEBUG "-g")
set(CMAKE_EXE_LINKER_FLAGS "")
set(CMAKE_EXE_LINKER_FLAGS "${CMAKE_EXE_LINKER_FLAGS} ${EXE_LINKER_FLAGS}")
include_directories(${INCLUDE_DIRECTORIES})
set(CMAKE_SUPPRESS_REGENERATION 1)
link_directories(${LINK_DIRECTORIES})
cmake_policy(SET CMP0065 NEW)
cmake_policy(SET CMP0083 OLD)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "/afs/cern.ch/work/k/kozuki/git/garfield/Examples/neBEM/CMakeFiles/CMakeTmp")
add_executable(cmTC_a7324 "/afs/cern.ch/work/k/kozuki/git/garfield/Examples/neBEM/CMakeFiles/FindOpenMP/OpenMPTryFlag.c")
target_link_libraries(cmTC_a7324  "-v" )
