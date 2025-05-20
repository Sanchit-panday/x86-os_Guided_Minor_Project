# x86-os_Guided_Minor_Project
Welcome to the **x86-os_Guided_Minor_Project** repository! This project is an educational initiative aimed at developing a simple operating system from scratch for x86 architecture. It serves as a guided minor project to deepen understanding of low-level system programming and OS concepts.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Building the OS](#building-the-os)
- [Running the OS](#running-the-os)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to build a basic operating system that can:

- Boot on x86 architecture
- Display simple text output
- Serve as a foundation for further OS development

This project is intended for educational purposes and is a work in progress. Contributions and suggestions are welcome!

## Features

- Bootloader implementation
- Kernel written in C and Assembly
- Basic screen output functionality
- Makefile for build automation
- Scripts for building and running the OS

## Directory Structure
.
├── build/ # Compiled binaries and ISO images
├── build_scripts/ # Scripts to automate the build process
├── run/ # Files related to running the OS
├── src/ # Source code for the OS (C and Assembly)
├── tools/ # Tools and utilities for development
├── Makefile # Build automation file
├── run.sh # Script to run the OS in an emulator
└── README.md # Project documentation


## Getting Started

### Prerequisites

To build and run this project, you need the following tools installed on your system:

- **GCC**: GNU Compiler Collection
- **NASM**: Netwide Assembler
- **QEMU**: Emulator for running the OS

### Installation

#### On Ubuntu/Debian:

```bash
sudo apt update
sudo apt install build-essential nasm qemu
