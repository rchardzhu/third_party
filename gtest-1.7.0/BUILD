package(default_visibility = ["//visibility:public"])

licenses(["restricted"]) # Google

cc_library(
    name = "gtest",
    srcs = [
        "src/gtest.cc",
        "src/gtest-death-test.cc",
        "src/gtest-filepath.cc",
        "src/gtest-printers.cc",
        "src/gtest-port.cc",
        "src/gtest-test-part.cc",
        "src/gtest-typed-test.cc",
        "src/gtest_main.cc",
    ],
    hdrs = glob([
        "include/**/*.h",
        "src/*.h"
    ]),
    includes = [
        ".",
        "./include",
    ],
    # gtest detects pthread, and the linker fails without it.
    linkopts = ["-pthread"],
)
