# ToyScript - A Minimalistic  Interpreted Esoteric Programming Language

## Introduction

Welcome to ToyScript, a distinctive, minimalistic, interpreted esoteric programming language, written in TypeScript and Deno, and designed to provide a unique coding experience. This language embraces unconventional syntax and features while incorporating familiar elements such as `let` and `const` declarations, functions, and versatile binary expressions. As of now the language isn't turing complete yet but I am working on it.

## Features

### Variable Declaration

#### `let`

The `let` keyword allows you to declare mutable variables, enabling dynamic storage for various data types.

[identifier] = [expression] ;

#### `const`

Use `const` to declare constants, ensuring that a variable's value remains unchanged once assigned.

const [identifier] = [expression] ;

#### Please note that variable declarations absolutely need to end with semicolons, however no semicolons are required for assignment or operations.

### Functions

Define modular code blocks with the `func` keyword, supporting parameterized functions for enhanced code organization and reusability.

fn [functionName]([parameter1], [parameter2], ...) { [functionBody] }

### Binary Expressions

Harness the power of binary expressions for arithmetic operations, including addition `+`, subtraction `-`, multiplication `*`, division `/`, and modulus `%`.

[result] = [operand1] [operator] [operand2]

## Examples

### Variable Declaration

    let x = 10;
    const pi = 3.14;

### Variable Assignment

    x = x + 1
    y = y / x
    z = y


### Functions

    fn add(a, b) {
        let sum = 0;
        sum = a + b
        print(sum)
    }


### Binary Expressions


    let result = add(5, 7) * 2;

### Print
    let x = 5;
    print(x)

## Usage

To run a program written in ToyScript, simply modify the `test.txt` file and save it and then use the following command to run the `main.ts` file:


    deno run -A main.ts


## Getting Started

1. Make sure that you have [Deno](https://docs.deno.com/runtime/manual/getting_started/installation) installed.
2. Fork and clone the repo.
3. Navigate to the `src` folder
4. Write your CrapScript program by modifying the `test.txt` file.
5. Run the `main.ts` file.



## Upcoming Features

The following is a list of planned features that will be implemented in the near future :

- Objects
- Loops
- Function to read user input
- Time
- Conditional Logic


