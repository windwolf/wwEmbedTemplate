cmake_minimum_required(VERSION 3.14 FATAL_ERROR)

set(CMSISDSP ${CMAKE_CURRENT_LIST_DIR}/src)

add_subdirectory(${CMSISDSP}/Source bin_dsp)
