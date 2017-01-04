test_sources = ['test_main.cpp']

includes = include_directories('../thirdy_party/catch/')

tester = executable('catch',
                    test_sources,
                    include_directories : includes,
                    install : false) 

test('Yascos Test', tester)
