add_executable( video video.c )
target_link_libraries( video Common )

configure_file(basemap.tga ${CMAKE_CURRENT_BINARY_DIR}/basemap.tga COPYONLY)
configure_file(lightmap.tga ${CMAKE_CURRENT_BINARY_DIR}/lightmap.tga COPYONLY)

