---
title: "Silly-ESP32"
description: "Modular mini-game platform for an ESP32-S3 touchscreen device with reusable game lifecycle, navigation, UI, and hardware abstractions"
external_url: "https://github.com/imaginarygarden/silly-esp32"
tags:
  - C++
  - ESP32
  - ESP-IDF
  - LVGL
  - Embedded Systems
---

Open-source embedded mini-game platform designed for an ESP32-S3 touchscreen device. Built around a modular architecture that separates game logic from hardware and UI concerns, making new games easier to implement, test, and reuse.

Key features:
- **Modular Game System:** Games are implemented as independent modules with a shared lifecycle and catalog
- **Touchscreen UI:** LVGL-based interface with menu navigation and reusable UI components
- **Hardware Integration:** Support for an ILI9341 SPI display and FT5x06-compatible touch controller
- **Testable Architecture:** Game rules are kept independent from ESP-IDF and LVGL where possible
- **Extensible Design:** Shared infrastructure handles navigation, sessions, views, and game registration

Tech stack: C++, ESP-IDF 5+, LVGL, CMake, ESP32-S3
