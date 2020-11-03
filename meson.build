project('ccan', 'c', default_options: ['c_std=gnu11'])

incs = [ include_directories('./')]
srcs = ['ccan/tal/tal.c', 'ccan/take/take.c', 'ccan/list/list.c']
ccan = static_library('ccan',
                      srcs,
                      include_directories : incs)

ccan_dep = declare_dependency(include_directories : incs,
                              link_with : ccan)
