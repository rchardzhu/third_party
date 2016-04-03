package(default_visibility = ["//visibility:public"])

licenses(["restricted"]) # Google

cc_library(
    name = "glog",
    srcs = [
        "src/demangle.cc",
        "src/logging.cc",
        "src/raw_logging.cc",
        "src/signalhandler.cc",
        "src/symbolize.cc",
        "src/utilities.cc",
        "src/vlog_is_on.cc",
    ],
    hdrs = glob([
        "src/*.h",
        "src/*/*.h",
    ]),
    includes = [
        "src/",
    ],
    # gtest detects pthread, and the linker fails without it.
    linkopts = ["-pthread"],
)
