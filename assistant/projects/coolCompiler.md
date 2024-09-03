# Cool Compiler Project

## Overview

The Cool Compiler project focuses on developing a compiler for the Classroom Object-Oriented Language (Cool). This project aims to create a functional compiler that translates Cool programs into MIPS assembly code, demonstrating key concepts in compiler design and implementation.

### Key Features

- Object-Oriented Language Support
- Automatic Memory Management
- Strong Static Typing
- MIPS Assembly Code Generation

### Languages Used

- Cool (source language)
- MIPS (target assembly language)
- Python (implementation language)

### Skills Demonstrated

- Compiler Design and Implementation
- Language Theory
- Parsing Techniques
- Semantic Analysis
- Code Generation

### Description

The Cool Compiler project involves several crucial stages in compiler design:

1. **Lexical Analysis**:
   - Tokenizes Cool source code
   - Handles keywords, identifiers, literals, and symbols

2. **Syntax Analysis**:
   - Parses the token stream using a parser generator tool
   - Constructs an abstract syntax tree (AST) representation of the program

3. **Semantic Analysis**:
   - Performs type checking and scoping analysis
   - Resolves symbol references and checks for semantic errors

4. **Intermediate Representation (IR)**:
   - Generates CIL (Cool Intermediate Language) as an intermediate form
   - Facilitates optimization and easier translation to target code

5. **Code Generation**:
   - Translates IR to MIPS assembly code
   - Implements object-oriented features in assembly

### Implementation Details

- Utilizes Python as the primary implementation language
- Generates MIPS assembly code for execution on a simulator
- Implements automatic memory management techniques
- Handles strong static typing rules during compilation

### Educational Significance

- Designed primarily for educational purposes in undergraduate compiler courses
- Incorporates features common in modern object-oriented languages
- Provides hands-on experience with compiler development

### Keywords

- Language theory
- CIL intermediate language
- Assembly
- Parsing-semantic-code generation
- Object-oriented language compiler