---
title: 01 - Basic elements of Java
date: 2025-09-22 17:04:06 +0200
categories: [HSLU BSc in Information and Cyber Security (ICS), HS25, PRG]
tags: [prg, java]     # TAG names should always be lowercase
author: johannes
description: Basics of datatypes in java.

# toc: false    # disable table of contents for this post
# comments: false   # disable commenting for this post
---

## Data types
As already demonstrated in the Article XYZ, computers do only actually 'understand' two states: `on` or `off`, or in otherwords `0` or `1`. So in the end, all data a computer processes needs to be so called binary, meaning either `0` or `1`. In order to save different types of data, so called data types have been defined. Data types can be unserstood as definitions that have been set by humans at some point, that define what types of data can be stored how.

| Type           | Data type  | Size    | Range                      |
|----------------|------------|---------|----------------------------|
| Logical        | **boolean**| 1 byte  | `true` or `false`          |
| Whole Number   | **byte**   | 1 byte  | `-2^7` → `2^7 - 1`         |
| Whole Number   | **short**  | 2 bytes | `-2^15` → `2^15 - 1`       |
| Whole Number   | **char**   | 2 bytes | `0` → `2^16 - 1`           |
| Whole Number   | **int**    | 4 bytes | `-2^31` → `2^31 - 1`       |
| Whole Number   | **long**   | 8 bytes | `-2^63` → `2^63 - 1`       |
| Floating Point | **float**  | 4 bytes | ~`±3.4E−38` → `±3.4E38`    |
| Floating Point | **double** | 8 bytes | ~`±1.7E−308` → `±1.7E308`  |


**Some things to consider:**

- *The data types in the table above are primitive (a.k.a. elementary or atomic) because they cannot be broken down any further and directly save data at machinecode (binary) level.*
- *`string` is not a primitive datatype but a reference type representing a sequence (concatenation) of `char` values.*
- Data types which can store both negative and positive values are of the type `signed` and those who can only store positive values (0 and up) are of the type `unsigned`.

## Variables

A variable consists of:

- Datatype and therefore Range
- Name
- Value

Value can be changed at will -> that why its called a *variable*.


# Basic Elements of Java Programming

## Variables
- Storage containers for data.
- Must have a datatype (e.g., `int`, `double`, `char`, `boolean`) and a name.
- Example: `int age = 21;`

## Data Types
- Define the type of data a variable can hold.
- Primitive types: `byte`, `short`, `int`, `long`, `float`, `double`, `char`, `boolean`
- Reference types: Objects like `String`, arrays, custom classes

## Strings
- Sequences of characters.
- Reference type, not primitive.
- Example: `String name = "John";`

## Operators
- Used to perform operations on variables and values.
- Examples:
  - Arithmetic: `+`, `-`, `*`, `/`, `%`
  - Relational: `==`, `!=`, `>`, `<`, `>=`, `<=`
  - Logical: `&&`, `||`, `!`

## Keywords
- Reserved words with special meaning in Java.
- Examples: `class`, `public`, `static`, `void`, `if`, `else`, `for`, `while`

## Comments
- Non-executable lines used to describe code.
- Single-line: `// comment`
- Multi-line: `/* comment */`

## Constants
- Fixed values that cannot be changed once assigned.
- Declared with the `final` keyword.
- Example: `final double PI = 3.14159;`

## Methods
- Blocks of code that perform a specific task.
- Can take parameters and return values.
- Example:
  ```java
  public int add(int a, int b) {
      return a + b;
  }
