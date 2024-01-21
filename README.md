# C - Stacks, Queues - LIFO, FIFO

This is a simple interpreter for Monty ByteCodes files written in C.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Supported Opcodes](#supported-opcodes)
- [File Structure](#file-structure)
- [Contributing](#contributing)

## Introduction

Monty 0.98 is a scripting language that is first compiled into Monty byte codes, similar to Python. This project aims to create an interpreter for Monty ByteCodes files.

## Getting Started

### Prerequisites

- GCC (GNU Compiler Collection)

### Installation

Clone the repository:

```bash
git clone https://github.com/JosephChinonso/monty.git
cd monty

```

Compile the code:

```bash

gcc main.c check_arguments.c malloc_failed.c initialize_arguments.c get_stream.c -o monty

```

## **Usage**

Run the Monty interpreter by providing the Monty ByteCode file as an argument:

```bash

./monty path/to/your/file.m

```

## **Supported Opcodes**

- **push**: Pushes an element onto the stack.
- **pall**: Prints all the values on the stack.
- **pint**: Prints the value at the top of the stack.
- **pop**: Removes the top element of the stack.
- **swap**: Swaps the top two elements of the stack.
- **add**: Adds the top two elements of the stack.
- **nop**: No operation; does nothing.

## **File Structure**

- **main.c**: Main entry point for the Monty interpreter.
- **check_arguments.c**: Functions for checking command-line arguments.
- **malloc_failed.c**: Error handling for malloc failures.
- **initialize_arguments.c**: Functions for initializing arguments.
- **get_stream.c**: Functions for getting the stream from the Monty ByteCode file.
- **monty.h**: Header file containing structures and function prototypes.

## **Contributing**

Feel free to contribute by opening issues or submitting pull requests.