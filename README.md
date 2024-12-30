# Rust Language Concept Wiki

This repository demonstrates various features of the Rust programming language, including core concepts, advanced techniques, and idiomatic Rust practices. The project contains well-structured code and test functions covering topics such as variables, control flow, traits, generics, memory management, concurrency, and more.

## Table of Contents
- [Features Covered](#features-covered)
- [Setup](#setup)
- [Usage](#usage)
- [Code Structure](#code-structure)

## Features Covered
The project explores a wide range of Rust concepts, including:

- **Basic Syntax**:
  - Variables and shadowing ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L88)).
  - Constants ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L366)).

- **Control Flow**:
  - If expressions ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L634)).
  - Loops ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L648)).
  - Pattern matching ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1113)).

- **Ownership and Borrowing**:
  - Ownership transfer ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L299)).
  - Borrowing ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L740)).
  - Lifetimes ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1333)).

- **Structs and Enums**:
  - Structs ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L924)).
  - Enums ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1014)).

- **Traits and Generics**:
  - Implementing traits ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1184)).
  - Using generics ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1222)).

- **Collections**:
  - Vectors ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1488)).
  - HashMaps ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1524)).

- **Memory Management**:
  - Smart pointers ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1575)).
  - Reference counting ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1613)).

- **Error Handling**:
  - Recoverable errors with `Result` ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1688)).
  - Option type ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1444)).

- **Concurrency**:
  - Unsafe code ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1745)).

- **Macros**:
  - Custom macros ([Code](https://github.com/VArtzy/rust-lang-concept/blob/main/src/main.rs#L1776)).

## Setup
1. **Install Rust**: Ensure you have Rust installed. If not, download it [here](https://www.rust-lang.org/tools/install).
2. **Clone the repository**:
   ```bash
   git clone https://github.com/VArtzy/rust-lang-concept.git
   cd rust-lang-concept
   ```
3. **Build the project**:
   ```bash
   cargo build
   ```
4. **Run tests**:
   ```bash
   cargo test
   ```

## Usage
- **Run the main application**:
   ```bash
   cargo run
   ```
- **Execute individual test modules**:
   ```bash
   cargo test --test module_name
   ```

## Code Structure
- **Main Module (`main.rs`)**: Contains the entry point and various feature demonstrations.
- **Submodules**:
  - `first`, `second`, `third`: Example modules for modularity and reusability.
  - `model`: Definitions of data structures and trait implementations.
