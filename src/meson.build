hztoml_incdir = include_directories('include')
hztoml = library('hztoml', ['toml.c'], version : '1.1.1', soversion : '3', include_directories : hztoml_incdir, install : true)
install_headers(['include/toml.h'], subdir : 'hztoml')
hztoml_dep = declare_dependency(include_directories : hztoml_incdir, link_with : hztoml)