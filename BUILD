package(default_visibility = ['//visibility:public'])

load('@io_bazel_rules_d//d:d.bzl', 'd_library')

d_library(name = 'reloaded',
          srcs = ['source/reloaded/package.d',
                  'source/reloaded/reloaded.d',
                  'source/reloaded/setjmp.d'],
          deps = ['//3rdparty/d/derelict-util',
                  '//3rdparty/d/fswatch'])

