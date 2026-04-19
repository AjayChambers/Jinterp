add_library(jinterp)

target_sources(jinterp
    PRIVATE
        # Add source files here, e.g.:
        # jinterp.cpp
)

target_include_directories(jinterp
    PUBLIC
        ${PROJECT_SOURCE_DIR}/include
)
