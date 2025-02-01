# Ownership by Rust

A simple Rust program that demonstrates how to concatenate two string slices using the `push_str()` method. This project is beginner-friendly and focuses on understanding basic Rust concepts like string manipulation, ownership, and function calls.

---

## Features

- Implements a function called `concatenate_strings` that concatenates two string slices and returns a new `String`.
- Demonstrates how to work with `String` and `&str` types in Rust.
- Provides a working example in the `main` function to test the implementation.

---

## Prerequisites

- Rust installed on your system. If you haven't installed Rust yet, you can follow the official guide: [Install Rust](https://www.rust-lang.org/tools/install).

---

## How It Works

1. The `concatenate_strings` function:
   - Takes two `&str` (string slices) as input.
   - Creates a new mutable `String`.
   - Uses the `push_str()` method to append the contents of the input slices to the new string.
   - Returns the resulting concatenated `String`.

2. The `main` function:
   - Defines two `String` variables (`string1` and `string2`) and initializes them with appropriate values.
   - Calls the `concatenate_strings` function with references to these variables.
   - Prints the concatenated result to the console.
     
