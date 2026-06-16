cmake_minimum_required(VERSION 3.16)
project(BoostHUD)

# Path to the cloned SDK
set(BAKKESMOD_SDK_PATH ${CMAKE_CURRENT_SOURCE_DIR}/bakkesmodsdk)

# Include the helper that defines bakkesmod_plugin()
include(${BAKKESMOD_SDK_PATH}/cmake/bakkesmod_plugin.cmake)

# Build our plugin
bakkesmod_plugin(BoostHUD BoostHUD.cpp)
