project (hanabi)

set(CMAKE_BINARY_DIR ${CMAKE_SOURCE_DIR}/bin)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR})

add_executable(hanabi src/hanabi.c)
target_link_libraries(hanabi ncurses)
