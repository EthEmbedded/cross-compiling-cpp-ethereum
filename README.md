# Cross-Compiling C++ Ethereum Client

Steps for Ubuntu/Debian:

- `sudo apt-get install gcc-arm-linux-gnueabihf`
- `sudo apt-get install g++-arm-linux-gnueabihf`
- `git clone --recursive https://github.com/ethereum/webthree-umbrella`
- `cd webthree-umbrella`
- `mkdir build`
- `cd build`
- `cmake .. -DCMAKE_TOOLCHAIN_FILE=cpp-ethereum-cross-compile.cmake`
- `make -j4`
 




Resources:

- Crosstool-ng - http://crosstool-ng.org/ - Helps to build gcc toolchain

- Cross-Compiling for Raspberry Pi - http://www.kitware.com/blog/home/post/426 - Blog regarding use of crosstool-ng

- Cmake & Cross Compiling resource - https://cmake.org/Wiki/CMake_Cross_Compiling

- Ethereum Ubuntu 64bit Install - https://github.com/ethereum/go-ethereum/wiki/Installation-Instructions-for-Ubuntu

- Ethereum Dependencies Breakdown - https://forum.ethereum.org/discussion/3635/cpp-ethereum-dependencies-breakdown 

- Simple Cross Compiler by installing package - http://askubuntu.com/questions/250696/cross-compile-for-arm
