cmake_minimum_required(VERSION 3.15)
project(gtkmm_start)

set(CMAKE_CXX_STANDARD 17)

find_package(PkgConfig)
pkg_check_modules(GTKMM gtkmm-3.0)
add_subdirectory(src)
