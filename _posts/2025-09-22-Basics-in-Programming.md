---
title: Basics in Programming (Using Java)
date: 2025-09-22 17:04:06 +0200
categories: [HSLU BSc in Information and Cyber Security (ICS), HS25, PRG]
tags: [prg, java]     # TAG names should always be lowercase
author: johannes
description: Basics of datatypes in java.

# toc: false    # disable table of contents for this post
# comments: false   # disable commenting for this post
---

## Variables

A variable consists of:

- Datatype and therefore Range
- Name
- Value

Value can be changed at will -> that why its called a *variable*.

## Elementary (Atomic) Types

| Type           | Datatype   | Size    | Range                      | Comment                                                                                      |
|----------------|------------|---------|----------------------------|----------------------------------------------------------------------------------------------|
| Logical        | **boolean**|         | `true` or `false`          | Only two possible values (*JVM may use 1 byte internally for storage*)                       |
| Whole Number   | **byte**   | 1 byte  | `-2^7` → `2^7 - 1`         | Signed 8-bit integer                                                                         |
| Whole Number   | **short**  | 2 bytes | `-2^15` → `2^15 - 1`       | Signed 16-bit integer                                                                        |
| Whole Number   | **char**   | 2 bytes | `0` → `2^16 - 1`           | Unsigned 16-bit integer for Unicode characters                                               |
| Whole Number   | **int**    | 4 bytes | `-2^31` → `2^31 - 1`       | Signed 32-bit integer                                                                        |
| Whole Number   | **long**   | 8 bytes | `-2^63` → `2^63 - 1`       | Signed 64-bit integer                                                                        |
| Floating Point | **float**  | 4 bytes | ~`±3.4E−38` → `±3.4E38`    | 32-bit IEEE 754 floating point (~7 decimal digits precision)                                 |
| Floating Point | **double** | 8 bytes | ~`±1.7E−308` → `±1.7E308`  | 64-bit IEEE 754 floating point (~15 decimal digits precision)                                |

> **String** is not a primitive datatype but a reference type representing a sequence (concatenation) of `char` values.

> **Signed types** → can store both negative and positive values.  
> **Unsigned types** → can only store positive values (0 and up).
