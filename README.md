# Minigrep

Minigrep is a simplified version of the classic Unix `grep` command, implemented in Rust as part of **Chapter 12 of The Rust Programming Language (the Rust Book)**.  

It allows you to search for a query string in a text file and print out all lines that contain the match.  

## Features
- Search for text within a file using a query string
- Case-sensitive and case-insensitive search
- Command-line argument parsing
- Error handling with `Result`
- Demonstrates idiomatic Rust concepts: ownership, borrowing, iterators, and closures
