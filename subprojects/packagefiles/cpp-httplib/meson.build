project('cpp-httplib',
  'cpp',
  version: '0.8.9',
  license: 'MIT'
)

cpp_httplib_dep = declare_dependency(include_directories: include_directories('.'))

if meson.version().version_compare('>=0.54.0')
  meson.override_dependency('cpp-httplib', cpp_httplib_dep)
endif
