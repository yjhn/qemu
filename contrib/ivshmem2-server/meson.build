executable('ivshmem2-server', files('ivshmem2-server.c', 'main.c'),
           dependencies: [qemuutil, rt],
           build_by_default: targetos == 'linux',
           install: false)
