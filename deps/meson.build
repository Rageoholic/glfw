include_deps_dir = include_directories('.')

glad_dep = declare_dependency(
    link_with: static_library('glad',
                              'glad_gl.c',
                              'glad/gl.h'),
    include_directories: include_deps_dir)


gladvk_dep = declare_dependency(
  link_with: static_library('glad_vk',
                            'glad_vulkan.c',
                            'glad/vulkan.h'),
  include_directories: include_deps_dir)

getopt_dep = declare_dependency(
    link_with: static_library('getopt',
                              'getopt.c',
                              'getopt.h'),
    include_directories: include_deps_dir)

tinycthread_dep = declare_dependency(
    link_with: static_library('tinycthread',
                              'tinycthread.c',
                              'tinycthread.h'),
    include_directories: include_deps_dir,
    dependencies: threads_dep)
