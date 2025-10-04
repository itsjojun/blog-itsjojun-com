---
title: Basic elements of Java
date: 2025-09-22 17:04:06 +0200
categories: [HSLU BSc in Information and Cyber Security (ICS), HS25, PRG]
tags: [prg, java]     # TAG names should always be lowercase
author: johannes
description: Java Datatypes

# toc: false    # disable table of contents for this post
# comments: false   # disable commenting for this post
---

## Datatypes

As already shown in Article *How Computers Work*, computers only really "understand" binara, so simply put: `0s` and `1s`. So in the end, all data a computer processes has to be binary data, meaning every image, word, or number must be represented as a long sequence of `0`s and `1`s.  

To make it easier for us humans to also work with base-10 (decimal) numbers inside a program in Java, there are so-called **data types**. These define how numbers (and other kinds of data) are stored and in what range. Basically, data types are just rules humans set up to decide what kind of data can be stored and how.

Here are the main ones in Java:

| Category       | Data type  | Size    | Range                      |
|----------------|------------|---------|----------------------------|
| Logical        | **boolean**| 1 byte* | `true` or `false`          |
| Whole Number   | **byte**   | 1 byte  | `-2^7` → `2^7 - 1`         |
| Whole Number   | **short**  | 2 bytes | `-2^15` → `2^15 - 1`       |
| Whole Number   | **char**   | 2 bytes | `0` → `2^16 - 1`           |
| Whole Number   | **int**    | 4 bytes | `-2^31` → `2^31 - 1`       |
| Whole Number   | **long**   | 8 bytes | `-2^63` → `2^63 - 1`       |
| Floating Point | **float**  | 4 bytes | ~`±3.4E−38` → `±3.4E38`    |
| Floating Point | **double** | 8 bytes | ~`±1.7E−308` → `±1.7E308`  |

**Some things to consider:**

- *In math, infinity is just taken for granted when calculating, but with computers and datatypes you can’t actually represent infinity — finite resources can only represent finite numbers.*
- *Technically, a `boolean` in Java doesn’t have a guaranteed size (it depends on the JVM), but it’s often stored as 1 byte for practicality.*
- *The data types in the table above are primitive (a.k.a. elementary or atomic) because they cannot be broken down any further and directly save data at machinecode (binary) level.*
- *Data types which can store both negative and positive values are of the type `signed` and those who can only store positive values (0 and up) are of the type `unsigned`.*

## Variables

A variable consists of:

- Datatype and therefore Range
- Name
- Value

Value can be changed at will -> that why its called a *variable*.

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
  `java
  public int add(int a, int b) {
      return a + b;
  }`
  