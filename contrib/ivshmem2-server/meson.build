executable('ivshmem2-server', files('ivshmem2-server.c', 'main.c'),
           dependencies: [qemuutil, rt],
           build_by_default: host_os == 'linux',
           install: false)
