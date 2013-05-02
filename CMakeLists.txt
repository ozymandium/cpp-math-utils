cmake_minimum_required(2.8)
project(mathutils)

find_package(Boost REQUIRED)

set(mathutils_SRC_DIRS ${PROJECT_SOURCE_DIR}/src)
set(mathutils_INCLUDE_DIRS ${PROJECT_SOURCE_DIR}/include)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)

# set(mathutils_SRCS
#     src/___
# )

include_directories(${mathutils_INCLUDE_DIRS})

# Boost
link_directories(${Boost_LIBRARY_DIRS})
include_directories(${Boost_INCLUDE_DIRS})