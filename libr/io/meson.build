files=[
'buffer.c',
'cache.c',
'desc.c',
'io.c',
'map.c',
'plugin.c',
'section.c',
'undo.c',
'p/io_bfdbg.c',
#'p/io_bochs.c',
'p/io_debug.c',
'p/io_default.c',
#'p/io_gdb.c',
'p/io_gzip.c',
'p/io_http.c',
'p/io_ihex.c',
'p/io_mach.c',
'p/io_malloc.c',
'p/io_mmap.c',
'p/io_null.c',
'p/io_procpid.c',
'p/io_ptrace.c',
#'p/io_qnx.c',
'p/io_r2k.c',
'p/io_r2k_linux.c',
#'p/io_r2k_windows.c',
'p/io_r2pipe.c',
'p/io_r2web.c',
'p/io_rap.c',
'p/io_self.c',
'p/io_shm.c',
'p/io_sparse.c',
'p/io_tcp.c',
#'p/io_w32.c',
#'p/io_w32dbg.c',
#'p/io_windbg.c',
#'p/io_zip.c',
]

r_io = shared_library('r_io', files,
  include_directories: include_directories(['../include']),
  link_with: [r_util, r_socket],
  c_args : '-DCORELIB=1',
  install: true
)