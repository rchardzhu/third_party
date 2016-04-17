# third_party

# Introduction
* [gtest](https://github.com/google/googletest) -- Google Test, Google's C++ test framework
* [glog](https://github.com/google/glog) -- C++ implementation of the Google logging module
* [gflags](https://github.com/gflags/gflags) -- A C++ library from Google that implements commandline flags processing
* [snappy](https://github.com/google/snappy.git) -- A fast compressor/decompressor from google, used by leveldb, hadoop, etc

# Build
* build gtest -- no need to configure
* build glog -- ./configure; cp config.h to src/ directory
* build gflags -- mkdir builds; cd builds; cmake ..; make; cp config.h, etc to src/ directory
* build snappy -- ./autogen.sh; ./configure
