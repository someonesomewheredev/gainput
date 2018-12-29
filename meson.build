project('gainput', 'cpp')

add_global_arguments('-Wall -Wpedantic -Wextra', language : 'cpp')

subdir('lib')

if(get_option('samples'))
    subdir('samples')
endif

if(get_option('tests'))
    subdir('test')
endif