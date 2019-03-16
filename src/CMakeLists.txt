add_library(Plumber INTERFACE)

target_include_directories(Plumber
    INTERFACE
    $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>
    $<INSTALL_INTERFACE:include/plumber>
)