# C++ Programming Playground

[![CI](https://github.com/mgpavankumar/playground/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/mgpavankumar/playground/actions/workflows/ci.yml)

A small C++ console exercise using standard headers and a warning-clean Hello World program.

**Author:** [M. G. Pavan Kumar](https://github.com/mgpavankumar)
**Status:** Educational project

## Features

- Standard C++ console output
- A repeatable GCC compile and output check

## Getting started

Install GCC or another C++ compiler. Clone this repository:

```bash
git clone https://github.com/mgpavankumar/playground.git
cd playground
```

```bash
g++ -std=c++17 -Wall -Wextra -Werror hai.cpp -o hello
./hello
```

Expected output: `hello world`. On Windows, run `.\hello.exe`.

## Project structure

| Path | Purpose |
| --- | --- |
| `hai.cpp` | Application logic and/or demonstration |

## Current behavior and limitations

This repository contains one introductory console exercise. It demonstrates compiler setup and standard output.

## Contributing

Keep changes focused, use synthetic data, and include steps or tests demonstrating the fix. Do not commit local configuration or credentials.
