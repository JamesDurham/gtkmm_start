link_directories( ${GTKMM_LIBRARY_DIRS} )
include_directories( ${GTKMM_INCLUDE_DIRS} )

add_executable(gtkmm_start main.cpp)

target_link_libraries(gtkmm_start ${GTKMM_LIBRARIES})