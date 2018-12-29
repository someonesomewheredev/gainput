project('gainput', 'cpp')

if meson.get_compiler('cpp').get_id() != 'msvc'
    add_global_arguments('-Wall', language : 'cpp')
    add_global_arguments('-Wpedantic', language : 'cpp')
    add_global_arguments('-Wextra', language : 'cpp')
endif


subdir('lib')

if(get_option('gainput_samples'))
    subdir('samples')
endif

if(get_option('gainput_tests'))
    subdir('test')
endif