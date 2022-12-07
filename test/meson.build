project('test_helloworld',
        'cpp',
        default_options : [
                'warning_level=3',
                'cpp_std=gnu++20'
        ])

gtest = dependency('gtest', main : false, method : 'system')

src = ['test_hello.cpp']
e = executable('test_hello', src, dependencies : gtest)
test('gtest test_hello', e, protocol : 'gtest')
