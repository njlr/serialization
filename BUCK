include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'boost-serialization',
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
    ('include/boost', '**/*.ipp'),
  ]),
  srcs = glob([
    'src/**/*.cpp',
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)

prebuilt_cxx_library(
  name = 'boost-serialization-headers',
  header_only = True,
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
    ('include/boost', '**/*.ipp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)
