libntr_link_args = []

libntr_exe = executable(
    'libntrsystem',
    sources: files('main.c'),
    dependencies: [ nitrosdk_dep, nitrosystem_dep ],
    link_args: [ libntr_link_args ],
    native: build_target != 'arm',
)
