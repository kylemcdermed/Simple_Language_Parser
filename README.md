# SimpleLangParser

A simple parser and Abstract Syntax Tree (AST) implementation for a toy language. This project demonstrates how to tokenize, parse, and represent language constructs like numeric literals, variables, and binary expressions in C++.

---

## Features

- **Parser**: Transforms tokens into an Abstract Syntax Tree (AST).
- **AST**: Represents core language constructs such as numbers, variables, binary expressions, and function calls.
- **Interactive Interface**: Accepts user inputs for parsing and AST generation.

---

## Code Overview

### 1. **Parser (`parser.cpp`)**
The parser is responsible for:
- Converting tokens into an Abstract Syntax Tree (AST).
- Handling:
  - **Primary expressions** (numbers, variables, parenthesized expressions).
  - **Binary expressions** with precedence rules.
  - **Function definitions and prototypes**.
  - **External declarations** and top-level expressions.

### 2. **AST (`ast.cpp`)**
The Abstract Syntax Tree (AST) includes:
- **Number Expressions**: Nodes representing numeric literals.
- **Variable Expressions**: Nodes for variable references.
- **Binary Expressions**: Nodes for binary operations (e.g., addition, subtraction).
- **Function Calls**: Nodes for calling functions.
- **Function Definitions**: Nodes representing function prototypes and bodies.

