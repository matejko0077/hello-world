# hello-world
I have super special pizza for all!
cmake_minimum_required(VERSION 3.6)
project(native)
add_subdirectory(libs/gui/libgui-arm64-android)
add_subdirectory(libs/ui/libui-arm64-android)
add_subdirectory(services/surfaceflinger/libsurfaceflinger-arm64-android)
add_subdirectory(services/surfaceflinger/surfaceflinger-arm64-android)
