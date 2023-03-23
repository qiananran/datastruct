cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

project(datastruce 
    VERSION 0.0.1
    PROJECT_DESCRIPTION     "about dataStruction"
    PROJECT_HOMEPAGE_URL    "https://github.com/qiananran/datastruct"
    LANGUAGE                C CXX
)

list(APPLE CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake")
include(BuildInfo)

add_subdirectory(external)

add_subdirectory(src)

add_subdirectory(docs)

add_subdirectory(test)

add_subdirectory(packaging)