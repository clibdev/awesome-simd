# Awesome SIMD

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repository collects impressive SIMD libraries and examples.

## Features Detection

### CPU Features

* [google/cpu_features](https://github.com/google/cpu_features) - C library to retrieve CPU features at runtime.
* [pytorch/cpuinfo](https://github.com/pytorch/cpuinfo) - C library to retrieve CPU features at runtime.
* [steinwurf/cpuid](https://github.com/steinwurf/cpuid) - C++ library to retrieve CPU features at runtime.
* [hi2p-perim/ssecheck.cpp](https://gist.github.com/hi2p-perim/7855506) - A code to check SSE/AVX instruction support.

## Math

### x86-64

* [reyoung/avx_mathfun](https://github.com/reyoung/avx_mathfun) - AVX-optimized implementations of mathematical functions.
* [ccsoni/AVX-and-AVX-512-mathfunc](https://github.com/ccsoni/AVX-and-AVX-512-mathfunc) - AVX/AVX-512-optimized implementations of mathematical functions.

### Various Architectures

* [JishinMaster/simd_utils](https://github.com/JishinMaster/simd_utils) - A header only library implementing common mathematical functions using SIMD intrinsics.

## Common Library

### ARM

* [ARM-software/optimized-routines](https://github.com/ARM-software/optimized-routines) - A collection of optimized implementations of common library functions for ARM CPUs.

## Machine Learning

### x86-64

* [oysteijo/simd_neuralnet](https://github.com/oysteijo/simd_neuralnet) - Feed-forward neural network implementation in C and AVX/AVX2/AVX-512.

## Posts

### x86-64

* [intel.com - Intel Intrinsics Guide](https://www.intel.com/content/www/us/en/docs/intrinsics-guide/index.html) - An online reference tool that lists and explains SIMD intrinsics.
* [nullprogram.com - Luhn Algorithm](https://nullprogram.com/blog/2022/04/30/) - A post that explains how to implement Luhn algorithm using SSE2.
