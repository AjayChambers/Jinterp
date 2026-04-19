enable_testing()

add_executable(jinterp_tests)

target_sources(jinterp_tests
    PRIVATE
        # Add test source files here, e.g.:
        # test_main.cpp
)

target_link_libraries(jinterp_tests
    PRIVATE
        jinterp
)

add_test(NAME jinterp_tests COMMAND jinterp_tests)
