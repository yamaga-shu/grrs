# grrs

This project is a command-line application (CLI) written in Rust for learning purposes. The name "grrs" is just a placeholder, but it can be read as "grep in Rust" or anything else you like.

## Overview

• This application demonstrates how to parse command-line arguments and process inputs in Rust.  
• It is intentionally kept simple for anyone who wants to explore the basics of creating CLI tools.

## Features

• Command-line argument parsing: Understand how to accept arguments from users.  
• File input handling: Demonstrates reading from files.  
• Search logic: A simple feature that allows you to look for specific text patterns.  

> Note: These functionalities can be expanded to suit more complex use cases.

## Installation

1. Install [Rust](https://www.rust-lang.org/tools/install) on your system.  
2. Clone this repository.  
3. Navigate to the project directory.  
4. Run:  
   ```
   cargo build --release
   ```
5. The compiled binary will be located at:
   ```
   target/release/grrs
   ```

## Usage

Once compiled, you can run the CLI tool by providing it with the required arguments. For example:
```
./grrs <pattern> <file_path>
```

This will search for <pattern> in the provided file.

## Why Rust?

Rust is a modern systems programming language focusing on performance and safety. When creating CLI tools, having a lightweight and efficient binary is essential, and Rust delivers on those fronts.

## Learning Resources

This project is inspired by examples in the following resource:
- [Command Line Applications in Rust](https://rust-cli.github.io/book/index.html)

Feel free to explore the chapters there to deepen your understanding of Rust CLI development.

