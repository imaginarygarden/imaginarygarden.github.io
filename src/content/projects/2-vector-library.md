---
title: "VectorLib"
description: "Lightweight generic dynamic array implementation in C with automatic resizing, safe memory management, testing, and CMake integration"
external_url: "https://github.com/imaginarygarden/vectorlib"
tags:
  - C
  - Data Structures
  - CMake
  - Memory Management
  - Unit Testing
---

Lightweight implementation of a generic dynamic array in C, inspired by the behavior of C++'s `std::vector`. Designed to provide type-agnostic contiguous storage while keeping memory management and error handling explicit and predictable.

Key features:
- **Generic Storage:** Stores arbitrary data types using `void*` and element-size metadata
- **Dynamic Resizing:** Automatically grows when full and shrinks when excess capacity is no longer needed
- **Memory Management:** Handles allocation, reallocation, and minimum-capacity rules internally
- **Error Handling:** Dedicated result codes provide explicit feedback for library operations
- **Reusable Library:** Supports direct CMake integration and `FetchContent`
- **Testing:** Includes Unity-based unit tests and benchmark support

Tech stack: C, CMake, Unity
