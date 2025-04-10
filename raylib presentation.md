---
title: "Raylib Codebase Overview"
---

# 📌 Project Overview

Raylib is a lightweight and easy-to-use library written in C for learning game development. It supports multiple platforms and allows for the creation of both 2D and 3D applications. The library is structured modularly and aims to be highly readable and accessible for beginners and intermediate developers.

---

# ❓ Questions & Answers

### What is Raylib?

Raylib is a simple and easy-to-use C programming library for developing graphics and multimedia applications.
 It's designed to be minimal yet powerful, emphasizing ease of use and educational value.
 
## What can I create with Raylib?
You can create games, tools, mobile apps, and any application requiring graphical display.

## What are the supported platforms?
Raylib supports Windows, Linux, macOS, Raspberry Pi, Android, and HTML5 (WebAssembly).

## Why is it coded in C?
C is a simple and low-level language that provides high performance without unnecessary abstraction layers.

## How does Raylib compare to Unity/Unreal/Godot?
Raylib is a lightweight programming library, unlike game engines that provide extensive toolsets and editors.

### What kind of apps can I build?

Raylib can be used to build:
- 2D and 3D games
- Educational tools
- Graphical simulations
- Multimedia applications

### Which platforms are supported?

- Windows
- Linux
- macOS
- Raspberry Pi
- Android
- HTML5 (via WebAssembly)

### Why is Raylib written in C?

C offers:
- High performance
- Low-level memory control
- Portability
- Simplicity without complex abstractions

---

# 🔍 Code Structure Overview

Raylib's source is divided into modules:

- `rcore`: Manages windows, input, and timing
- `rshapes`: Functions for drawing 2D shapes and handling collisions
- `rmodels`: Functions for handling and rendering 3D models
- `rtextures`: Manages image loading and texture manipulation
- `raymath`: Math utilities for vectors, matrices, and quaternions
- `raudio`: Handles sound and music playback
- `rgestures`: Detects touch gestures for mobile platforms

Each module typically has both `.h` and `.c` files that define public interfaces and internal implementations.

---

# 🧱 Data Types Used

### Structs
Used extensively to define core objects like:
- `Vector2`, `Vector3`, `Vector4` for spatial data
- `Rectangle`, `Color`, `Image`, `Texture2D`, `Model` for game assets

### Arrays
Used for:
- Vertices, textures, and image data
- Managing collections of game objects or renderable elements

### Enums
Used for:
- Defining constants (e.g., gesture types, texture formats, key codes)

### Pointers
Enable dynamic memory allocation and modular resource handling.

---

# ⚖️ Trade-offs

| Feature                        | Pros                                            | Cons                                                 |
|-------------------------------|--------------------------------------------------|------------------------------------------------------|
| **Written in C**              | Fast, low-level control                         | Manual memory management, no OOP                     |
| **Modular design**            | Easy to understand and use separately           | Requires some boilerplate to set up each module      |
| **No GUI editors**            | Full control, clean API                         | No visual design tools                               |
| **Cross-platform support**    | Runs on many systems                            | Needs platform-specific builds/adjustments           |
| **Self-contained**            | No external dependencies by default             | Larger initial setup if extending functionality      |

---

# ✅ Summary

Raylib is a robust choice for developers who want to build games or interactive apps from the ground up, especially those learning programming concepts. Its clear structure and lightweight design make it perfect for experimentation and education.

For more, visit [https://www.raylib.com](https://www.raylib.com) 
