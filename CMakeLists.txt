add_library(imgui-docking imgui.cpp imgui_draw.cpp imgui_demo.cpp imgui_widgets.cpp imgui_tables.cpp
  backends/imgui_impl_opengl3.cpp backends/imgui_impl_glfw.cpp misc/cpp/imgui_stdlib.cpp)
target_include_directories(imgui-docking PUBLIC ${CMAKE_CURRENT_SOURCE_DIR} PRIVATE ../glfw/include)
