# Linux System Programming
This repository includes three fully functional system-level C projects, each developed to demonstrate practical use of Linux system calls and low-level programming


Project include:
- **File Organizer**: Sorts files by extension via a custom `tree` and `arrange` command-line tool
- **Cleanup Daemon**: Runs background processes that monitor and organize directories in real time
- **EXT2 Image Analyzer**: Parses raw ext2 filesystem images to display structure and contents without using external libraries


Each project is implemented from scratch in C, runs in the terminal.

## Projects
### 1. File Organizer: [ssu-cleanup](https://github.com/jaeunda/lsp-p1)
- This CLI-based tool organizes files in a given directory based on their extensions.
- This project focuses on file I/O, command parsing, and linked list representation of directory structures.
### 2. Cleanup Daemon: [ssu-cleanupd](https://github.com/jaeunda/lsp-p2)
- This tool runs as a daemon that monitors specified directories and organizes newly added files periodically.
- This project focuses on daemon process management, configuration handling, file locking, and exception handling in a system environment.
### 3. EXT2 Image Analyzer: [ssu-ext2](https://github.com/jaeunda/lsp-p3)
- This CLI program parses and analyzes ext2 disk image files to display directory structures and file contents.

## Requirements
- Linux-based OS (e.g., Ubuntu)
- gcc
- Each project includes its own `Makefile`

