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

- Datatype and  therefore Scope
  - *(e.g. type: int -> -2^31 - 2^31-1)*
- Name
- Value

Value can be changed at will -> that why its called a *variable*.

## Elementary (Atomic) Types

| Type | Datatype | Size
|------|------|------
|Whole Number | byte | 1 byte
|Whole Number | short/char | 2 bytes
|Whole Number | int | 4 bytes
|Whole Number | long | 8 bytes
|Floating Point | float | 4 bytes
|Floating Point | double | 8 bytes

> **!** short and char -> same datatype but different rendering. While *short* is being rendered as e.g. '?' in ASCII and UTF-8 to '00111111', char would display just the character '?'.

> **!** *string* ist kein Datentyp sondern ein Referenztyp oder auch ein Verkettung von mehreren *char* Datentypen.
