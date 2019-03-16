add_executable(PluberTest
    CatchMainConfig.cc
    TestPipe.cc
)

target_link_libraries(PluberTest Plumber)