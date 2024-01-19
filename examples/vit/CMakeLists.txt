set(TEST_TARGET vit)
add_executable(${TEST_TARGET} vit.cpp main.cpp)
target_link_libraries(${TEST_TARGET} PRIVATE ggml common common-ggml)

