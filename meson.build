project('libbootimg', 'c')

i = include_directories('include')
l = static_library('bootimg', 'src/libbootimg.c', include_directories : i)
libbootimg = declare_dependency(include_directories : i,
                                link_with: l)
