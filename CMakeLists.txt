cmake_minimum_required(VERSION 3.1)
project(SHAPESBrush)

set(CMAKE_MODULE_PATH ${CMAKE_CURRENT_SOURCE_DIR}/cmake)

add_subdirectory(source)

install(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/modules/SHAPESBrush/icons DESTINATION ./SHAPESBrush)
install(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/modules/SHAPESBrush/scripts DESTINATION ./SHAPESBrush)
install(FILES ${CMAKE_CURRENT_SOURCE_DIR}/SHAPESBrush.mod DESTINATION .)
