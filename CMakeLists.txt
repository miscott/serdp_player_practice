#
# project: serdp_player_NEW
#
cmake_minimum_required(VERSION 2.8)
project(serdp_player_NEW)
# include the fips main cmake file
get_filename_component(FIPS_ROOT_DIR "../fips" ABSOLUTE)
include("${FIPS_ROOT_DIR}/cmake/fips.cmake")

# include_directories(src)
fips_setup()
# fips_add_subdirectory(src/...)
# fips_add_subdirectory(src/...)
fips_finish()


