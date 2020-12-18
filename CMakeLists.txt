# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.8)

project ("CMakeProject1")

set(CMAKE_CXX_CLANG_TIDY clang-tidy -warnings-as-errors=* -checks=-*,readability-*)

# Include sub-projects.
add_subdirectory ("CMakeProject1")
