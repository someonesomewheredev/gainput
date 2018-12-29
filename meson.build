project('gainput', 'cpp')

add_global_arguments('-Wall -Wpedantic -Wextra', language : 'cpp')

subdir('lib')

option('samples', type: 'boolean', description: 'Build Samples for Gainput', false)
option('tests', type: 'boolean', description: 'Build Tests for Gainput', false)

if(get_option('samples'))
    subdir('samples')
endif

if(get_option('test'))
    subdir('test')
endif