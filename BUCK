cxx_library(
  name = 'date',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', '*.h'),
  ],
  excludes = glob([
    'ios.h',
    'tz_private.h',
  ])),
  headers = subdir_glob([
    ('', 'tz_private.h'),
  ]),
  srcs = glob([
    '*.cpp',
  ]),
  compiler_flags = [
    '-std=c++11',
  ],
  visibility = [
    'PUBLIC',
  ],
)
