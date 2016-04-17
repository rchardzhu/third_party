# third_party

# Introduction
* [gtest](https://github.com/google/googletest) -- Google Test, Google's C++ test framework
* [glog](https://github.com/google/glog) -- C++ implementation of the Google logging module
* [gflags](https://github.com/gflags/gflags) -- A C++ library from Google that implements commandline flags processing
* [snappy](https://github.com/google/snappy) -- A fast compressor/decompressor from google, used by leveldb, hadoop, etc
* [re2](https://github.com/google/re2) -- A fast, safe, thread-friendly alternative to backtracking regular expression engines like those used in PCRE, Perl, and Python
* [protobuf](https://github.com/google/protobuf) -- Google's data interchange format https://developers.google.com/protocol-buffers/

# Build
* build gtest -- no need to configure
* build glog -- ./configure; cp config.h to src/ directory
* build gflags -- mkdir builds; cd builds; cmake ..; make; cp config.h, etc to src/ directory
* build snappy -- ./autogen.sh; ./configure
* build re2 -- already support bazel
* build protobuf -- already support bazel
