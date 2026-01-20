# MiniShell – 42 School Project

This repository contains my **MiniShell** project from 42 School. MiniShell is a simple UNIX shell implementation that supports basic commands, pipelines, redirections, and environment management.

---

## Overview

`MiniShell` is designed to mimic a simplified version of a UNIX shell. The project teaches **process management, input/output redirection, and command parsing** in C.

### Features

* Execute built-in commands (`cd`, `echo`, `pwd`, `export`, `unset`, `env`, `exit`)
* Execute external commands via `fork` and `execve`
* Support for **pipes** to chain commands
* Input and output redirection (`<`, `>`, `>>`)
* Signal handling (Ctrl+C, Ctrl+)
* Environment variable management
* Error handling for invalid commands and syntax

### Installation & Build

```bash
git clone <repo-url>
cd minishell  # change to the project directory
make
./minishell
```

### Usage

* Type commands as you would in a normal shell.
* Supports chaining commands with `|` and redirecting input/output.
* Use `exit` to quit the shell.

### Notes

* Focuses on **system programming concepts**: process control, signals, and file descriptors.
* Teaches parsing user input and handling errors gracefully.
* Core project for understanding how shells work internally.

---

## Languages

* C — 96.8%
* Makefile — 3.2%
