cmake_minimum_required(VERSION 3.16)
project(BoostHUD)
add_subdirectory(bakkesmodsdk EXCLUDE_FROM_ALL)
bakkesmod_plugin(BoostHUD BoostHUD.cpp)
