# tinyosc

[![Release is 0.1](http://img.shields.io/badge/release-0.1-blue.svg?style=flat)](https://github.com/ddiakopoulos/tinyosc)
[![License is zlib](http://img.shields.io/badge/license-zlib-blue.svg?style=flat)](https://opensource.org/licenses/Zlib)

Platform | Build Status |
-------- | ------------ |
VS2019 x64  | |
macOS/Linux | |

tinyosc is a "modern c++" upgrade of Julien Pommier's [oscpkt](http://gruntthepeon.free.fr/oscpkt/). It exists within a single header file, includes CMake support to build as a static library, and offers a cross-platform UDP *or* TCP transport layer derived from the public domain [zed_net](https://github.com/Smilex/zed_net) single-header socket library. 

# License

This project is licensed under zlib. The socket header is released into the public domain. 