libusermode_h = include_directories(
    '..', '../..'
)
libusermode = static_library('usermode',
    'userhook.cpp',
    'userhook_pf.cpp',
    'userhook_inject.cpp',
    'running.cpp',
    'printers/printers.cpp',
    'printers/utils.cpp',

    dependencies : deps,
    include_directories : libusermode_h,
    link_with : libdrakvuf
)
