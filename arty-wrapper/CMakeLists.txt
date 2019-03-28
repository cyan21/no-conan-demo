
add_library(arty-wrapper STATIC wrapper.cpp)
target_include_directories (art PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
target_link_libraries (arty-wrapper LINK_PUBLIC art)
