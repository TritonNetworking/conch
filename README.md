
The Conch control plane
=======================

A sub-second data center control plane focusing on support for
reconfigurable circuit switching.

The gtest integration and Travis-CI integration features are based on a demo
(https://github.com/bast/gtest-demo) authored by Radovan Bast under a BSD-3
license.

## How to build the code

```
git clone --recursive git@github.com:TritonNetworking/conch.git
cd conch
mkdir build
cd build
cmake ..
make -j
make test
```
