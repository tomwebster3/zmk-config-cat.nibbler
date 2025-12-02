zephyr_library()
zephyr_library_sources(bongo_cat.c)
zephyr_library_include_directories(.)
zephyr_library_compile_definitions(BONGO_CAT_FRAME_COUNT=2)

