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
  - (e.g. type: int -> -2^31 - +2^31)
- Name
- Value

Value can be changed at will -> that why its called a *variable*.

## Elementary (Atomic) Types

- Nummerischer Typ
- Ganzzahlig
  - byte -> 1 byte
  - short / char -> 2 byte -> short und char ist dasselbe, jedoch wird char gerendert (z.B '?' ist in ascii/utf-8 '00111111') -> gerendert -> fragezeichen würde anzeigt werden, ungerendert würde maschienencode (binärdarstellung) angezeigt werden.
  - int -> 4 bytes
    - long -> 8 bytes
- Fliesskommatyp
  - float -> 4 bytes
  - double -> 8 bytes

> *string* ist kein Datentyp sondern ein Referenztyp oder auch ein Verkettung von mehreren *char* Datentypen.
