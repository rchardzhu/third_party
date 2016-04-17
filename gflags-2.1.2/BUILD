package(default_visibility = ["//visibility:public"])

licenses(["notice"])
exports_files(["COPYING.txt"])

cc_library(
    name = 'gflags',
    srcs = [
        'src/gflags.cc',
        'src/gflags_reporting.cc',
        'src/gflags_completions.cc',
    ],
    hdrs = [
        'src/config.h',
        'src/gflags.h',
        'src/gflags_declare.h',
        'src/gflags_gflags.h',
        'src/gflags_completions.h',
        'src/mutex.h',
        'src/util.h',
    ],
    includes = ['src/'],
    linkopts = ['-lpthread'],
#warning = 'no'
)
