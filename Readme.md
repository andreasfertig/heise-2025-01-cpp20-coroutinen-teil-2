# Companion Source Code for "C++20s Coroutinen - Coroutinen kennen- und verwenden lernen"  Edition

[![Build Status](https://github.com/andreasfertig/heise-2025-01-cpp20-coroutinen-teil-2/workflows/ci/badge.svg)](https://github.com/andreasfertig/heise-2025-01-cpp20-coroutinen-teil-2/actions/) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE.txt)

![Book cover](.artwork/cover.png)

## Code examples

This repository contains runnable source code examples from the  edition of [C++20s Coroutinen - Coroutinen kennen- und verwenden lernen](https://www.heise.de/select/ix/2025/01), by [Andreas Fertig](https://andreasfertig.com).

### The layout of the examples

The examples are separated into different directories based on how they appear in the book.

### Running the examples

The examples are in a single `.cpp` file that can be easily executed in any IDE. There is also an `CMakeLists.txt` which can generate IDE projects or be used to compile the example in a terminal.
This repo contains a top-level `CMakeLists.txt`, which does build all the examples.

### Building the examples

You can select the compiler by setting the `CXX` environment variable.

```
mkdir heise-2025-01-cpp20-coroutinen-teil-2
cd heise-2025-01-cpp20-coroutinen-teil-2
git clone https://github.com/andreasfertig/heise-2025-01-cpp20-coroutinen-teil-2 .
mkdir build
cd build
cmake ../
cmake --build . -j
```

After that, you find all the executables in `heise-2025-01-cpp20-coroutinen-teil-2/build/bin`.

Some examples use the latest C++ standard, so you will need a modern compiler to compile them. The latest stable versions of GCC or [Clang](https://releases.llvm.org/) are recommended. The code is not tested but is also expected to work with MSVC.

## License

The source code is released under the [MIT License](/LICENSE.txt).