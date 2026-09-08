add_library(OpenStreamCore STATIC
    src/version.cpp
)

target_include_directories(OpenStreamCore
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}/include
)

target_compile_features(OpenStreamCore
    PUBLIC cxx_std_20
)
