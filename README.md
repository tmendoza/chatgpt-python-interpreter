# Simple Scheme Interpreter for ChatGPT

This repository contains a simple Scheme interpreter that is designed to be run within OpenAI's ChatGPT with Python coding capabilities enabled. The interpreter is written in Python and allows for the execution of basic Scheme commands and programs.

## Design

The interpreter, based on Peter Norvig's `(How to Write a (Lisp) Interpreter (in Python))` article, is a minimal yet functional implementation of Scheme. The design is straightforward: it parses Scheme expressions, tokenizes them into meaningful symbols, literals, and lists, and then evaluates these expressions within a predefined environment.

## Purpose

The purpose of this interpreter is to provide a lightweight and accessible way to run Scheme code in environments where a full Scheme interpreter is not available, such as within the ChatGPT interface. It's intended for educational purposes, quick Scheme scripting, and as a demonstration of language interpreter design in Python.

## Uses

- **Educational Tool**: Learn the basics of Scheme through interactive execution.
- **Scripting**: Run simple Scheme scripts to perform calculations or demonstrate concepts.
- **Interpreter Design**: Study the construction of a Lisp interpreter written in another high-level language.

## Features

- Basic arithmetic and logical operations
- Definition of variables and procedures
- Lambda expressions for creating anonymous functions
- Conditional expressions with `if`
- Environment handling with lexical scoping
- Support for core Lisp concepts such as quoting and cons cells

Please note that this interpreter is not fully R5RS-compliant and is intended for basic use cases and learning purposes.

## Contribution

Contributions are welcome. If you find a bug or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is open source and available under the MIT License.
