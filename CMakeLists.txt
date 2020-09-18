cmake_minimum_required(VERSION 3.17)
project(imgui)

set(CMAKE_CXX_STANDARD 14)

add_library(imgui STATIC imconfig.h imgui.cpp imgui.h imgui_demo.cpp imgui_draw.cpp imgui_internal.h imgui_widgets.cpp imstb_rectpack.h imstb_textedit.h imstb_truetype.h)
target_include_directories(imgui PUBLIC ./)
