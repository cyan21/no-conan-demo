#add_library(art SHARED artifactory.cpp)
add_library(art STATIC artifactory.cpp)
target_include_directories (art PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
#install(TARGETS arty DESTINATION bin)
