hztoml_incdir = include_directories('include')
hztoml = library('hztoml', ['toml.c'], version : '1.2.5', soversion : '5', include_directories : hztoml_incdir, install : true)
install_headers(['include/toml.h'], subdir : 'hztoml')
hztoml_dep = declare_dependency(include_directories : hztoml_incdir, link_with : hztoml)