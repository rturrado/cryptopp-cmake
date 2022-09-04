# Crypto++ CMake
Fork of [noloader/cryptopp-cmake](https://github.com/noloader/cryptopp-cmake) which, at the same time, is a fork of [weidai11/cryptopp](https://github.com/weidai11/cryptopp), a C++ library of cryptographic schemes.

This fork:
- Changed `BUILD_TESTING` option to `CRYPTOPP_CMAKE_BUILD_TESTS`, and set it to OFF, to avoid building tests unless requested.
- Changed `BUILD_DOCUMENTATION` option to `CRYPTOPP_CMAKE_BUILD_DOCUMENTATION`.
- Fixed cmake_minimum_required deprecation warning when adding Crypto++ CMake to another project.
- Added checks for CMake policies CMP0126 and CMP0128.
