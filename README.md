# CSE233 - Assignment 2

Operating Systems assignment covering process creation with `fork()`, linking multiple C files, and checking dynamic libraries using `ldd`.

## Files in this Repo

- `process_creation.c` - creates a child process using `fork()` and prints the parent and child PIDs.
- `file1.c` and `file2.c` - two separate C files compiled and linked together into one executable.
- `simple_program.c` - basic C program used to inspect shared libraries with `ldd`.
- `Makefile` - compiles all three programs with `gcc`.
- `Code_Explaination.txt` - my explanation of what each C program does.
- `Linker-Loader_Explaination.txt` - my explanation of the Linker and Loader roles.
- Screenshots showing compilation and outputs.

## Installation

You need `gcc` and `make` installed on Linux (Ubuntu/Debian):

```bash
sudo apt update
sudo apt install gcc make
