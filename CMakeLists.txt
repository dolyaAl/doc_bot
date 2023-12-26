cmake_minimum_required(VERSION 3.19)

set(PROJECT_NAME doc_bot)

project(${PROJECT_NAME})

add_subdirectory(main)

set_property(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} PROPERTY VS_STARTUP_PROJECT Docs)
