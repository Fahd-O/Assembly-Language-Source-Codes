# Assembly Language Source Codes

## Overview

This repository contains a single Assembly Language program, `AddTwo.asm`, which I created during my university coursework in the "CSC 204: Assembly Language" course. The file demonstrates basic operations in Assembly Language, focusing on adding two 32-bit integers. Created and completed on Sat, 24th Jul 2021.

## Learning Objectives

The objective of this exercise was to understand and practice:

- Basic Assembly Language syntax.
- Using registers for arithmetic operations.
- Calling system procedures (e.g., `ExitProcess`).

## File Description

- **`AddTwo.asm`**: A program that adds two 32-bit integers (5 and 6) using the `eax` register and outputs the result.

## Tech Stack

- **Language**: Assembly Language
- **Assembler**: MASM (Microsoft Macro Assembler) or compatible.

## Usage

1. Assemble the code using MASM or any compatible assembler:

   ```bash
   ml /c /coff AddTwo.asm
   ```

2. Link the object file to create an executable:

   ```bash
   link /subsystem:console AddTwo.obj
   ```

3. Run the executable:

   ```bash
   AddTwo.exe
   ```

## Screenshots

Here's a screenshots of the project folder properties:

![Project Folder Properties Screenshot](./img/Assembly%20lang.png)

## Future Improvements

No additional updates are planned as this repository serves as an archive of a learning exercise.
