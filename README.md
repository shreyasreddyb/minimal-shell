# Very Minimal Shell

A tiny Linux shell written in C and x86_64 assembly.  
The goal of this project is to demonstrate how a shell can be implemented with **as little code as possible**, relying directly on system calls.

⚠️ This is a proof-of-concept for learning purposes.  
It is **not secure** and **not suitable for production use**.

---

## Features

- Reads and executes commands directly (no parsing, no arguments).
- Uses raw system calls (`read`, `write`, `fork`, `execve`, `waitid`, `_exit`).
- Very small codebase (fits in a few source files).
- Includes a **pure assembly implementation** (`pure-asm-implementation/shell.asm`).

---

## Repository Structure


---

## Build & Run

### Prerequisites
- Linux (x86_64)
- `gcc`, `as`, `ld` (GNU binutils)

### Steps
```bash
# Build the shell
./build.sh

# Run
./init
