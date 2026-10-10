# C++ Programming Playground

A small C++ learning repository containing a console-based Hello World exercise.

**Author:** [M. G. Pavan Kumar](https://github.com/mgpavankumar)  
**Status:** Educational project

## Features

- Basic program structure and a `main()` entry point
- Console output using `cout`

## Getting started

Install a C++ compiler such as GCC. Clone this repository:

```bash
git clone https://github.com/mgpavankumar/playground.git
cd playground
```

Apply the header correction described below before compiling.

```bash
g++ hai.cpp -o hello
./hello
```

## Project structure

| Path | Purpose |
| --- | --- |
| `hai.cpp` | Hello World exercise |

## Current behavior and limitations

The current source uses the legacy `<iostream.h>` header. Replace it with `<iostream>` before compiling with a modern compiler. On Windows, run the resulting executable as `.\hello.exe`.

## Planned improvements

- Use the standard C++ header and consistent formatting
- Add further exercises with sample input and output

## Contributing

Open an issue describing the problem or proposed improvement. Keep pull requests focused and include the steps used to verify changes. Use sample data and keep credentials out of commits.

## Verification

This documentation was checked against the committed source files, dependency declarations, and route definitions. Installation, compilation, database setup, and runtime behavior have not been verified by this documentation update. There is no automated test suite in the current repository.
