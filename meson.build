project('imgui', 'cpp')

include_dirs = include_directories('.')
sources = ['imgui.cpp', 'imgui_demo.cpp', 'imgui_draw.cpp']

imgui = library(
  'imgui',
  sources,
  include_directories: include_dirs
)

project_dep = declare_dependency(
  link_with : imgui,
  include_directories : include_dirs)
