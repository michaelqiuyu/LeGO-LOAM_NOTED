cmake_minimum_required(VERSION 3.17)
project(LeGO_LOAM_NOTED_my)

set(CMAKE_CXX_STANDARD 14)

include_directories(src/LeGO-LOAM/include)

add_executable(LeGO_LOAM_NOTED_my
        src/LeGO-LOAM/include/utility.h
        src/LeGO-LOAM/src/featureAssociation.cpp
        src/LeGO-LOAM/src/imageProjection.cpp
        src/LeGO-LOAM/src/mapOptmization.cpp
        src/LeGO-LOAM/src/transformFusion.cpp)
