if (DEFINED PICO_BOARD AND PICO_BOARD STREQUAL "pico_w")
    include(picow_basic_request.cmake)
else()
    include(linux_basic_request.cmake)
endif ()