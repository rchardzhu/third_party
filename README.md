# third_party

# Introduction
* [gtest](https://github.com/google/googletest) -- Google Test, Google's C++ test framework
* [glog](https://github.com/google/glog) -- C++ implementation of the Google logging module
* [gflags](https://github.com/gflags/gflags) -- A C++ library from Google that implements commandline flags processing

# Build
* Build gtest -- no need to configure
* Build glog -- ./configure; cp config.h to src/ directory
* Build gflags -- mkdir builds; cd builds; cmake ..; make; cp config.h, etc to src/ directory
