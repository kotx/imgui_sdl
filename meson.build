project('imgui_sdl', 'cpp',
    license: 'MIT')

include = include_directories('.')

imgui_sdl = shared_library('imgui_sdl', 'imgui_sdl.cpp',
    dependencies: [
        dependency('imgui', required: true),
        dependency('sdl2', required: true),
    ],
    include_directories: include)

imgui_sdl_dep = declare_dependency(include_directories: include, link_with: imgui_sdl)
