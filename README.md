OpenCL-Project-GameOfLife
=========================

A comparison between a serial implementation of Game of Life with a serial algorithm and a parallel one using OpenCL, created for a college project. 

Special thanks to [Gabriele](https://github.com/Gabriele91) for the support about OpenCL debugging.

## Requirements

* Your favourite IDE or build automation software for C/C++
* [CMake](http://www.cmake.org/)
* OpenCL SDK
  * [Intel-OpenCL](https://software.intel.com/en-us/intel-opencl)
  * [Nvidia Cuda](https://developer.nvidia.com/cuda-zone)
  * [AMD APP-SDK](http://developer.amd.com/tools-and-sdks/opencl-zone/amd-accelerated-parallel-processing-app-sdk/)

## How to build

Use CMake to create and build the project or create a project yourself using the sources in the src directory. Remember to set the working directory of the project on src folder, or copy the kernel in the same directory of the binary because the main program require kernel.cl file, is loaded at running time and of course you have to manage the OpenCL stuff anyway.

## Documentation

[Project informations and considerations](https://github.com/MircoT/OpenCL-Project-GameOfLife/blob/master/DOCUMENTATION.md).

## Credits

CMake module for OpenCL was found here: https://gitorious.org/findopencl.

## License

The MIT License (MIT)

Copyright (c) 2014 Mirco

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
