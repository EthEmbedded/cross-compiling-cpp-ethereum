# Cross-Compiling C++ Ethereum Client

Steps:

- Download & build Crosstool-ng

- `git clone cpp-ethereum`

- When running cmake in folder `~/cpp-ethereum/build` pass the following: `cmake .. -DCMAKE-TOOLCHAIN=cpp-ethereum-cross-compile.cmake`




Resources:

- Crosstool-ng - http://crosstool-ng.org/ - Helps to build gcc toolchain

- Cross-Compiling for Raspberry Pi - http://www.kitware.com/blog/home/post/426 - Blog regarding use of crosstool-ng

- Cmake & Cross Compiling resource - https://cmake.org/Wiki/CMake_Cross_Compiling

- Ethereum Ubuntu 64bit Install - https://github.com/ethereum/go-ethereum/wiki/Installation-Instructions-for-Ubuntu

- Ethereum Dependencies Breakdown - https://forum.ethereum.org/discussion/3635/cpp-ethereum-dependencies-breakdown? 

- Simple Cross Compiler by installing package - http://askubuntu.com/questions/250696/cross-compile-for-arm
