---
marp: true
theme: uncover
class: invert
math : mathjax
---

# Raylib Project Overview

## Introduction
Raylib is a C-based programming library designed for graphics and multimedia applications. It is intended to be simple and easy to use, making it suitable for small to mid-sized 2D games and multimedia applications.

## Key Features
•⁠  ⁠Lightweight and simple API
•⁠  ⁠Supports multiple platforms including Windows, Linux, macOS, and Raspberry Pi
•⁠  ⁠Written in C for performance and simplicity
•⁠  ⁠Includes multiple bindings for other programming languages

---

# Frequently Asked Questions

## What is Raylib?
Raylib is a simple and easy-to-use C programming library for developing graphics and multimedia applications.

## What can I create with Raylib?
You can create games, tools, mobile apps, and any application requiring graphical display.

## What are the supported platforms?
Raylib supports Windows, Linux, macOS, Raspberry Pi, Android, and HTML5 (WebAssembly).

## Why is it coded in C?
C is a simple and low-level language that provides high performance without unnecessary abstraction layers.

## How does Raylib compare to Unity/Unreal/Godot?
Raylib is a lightweight programming library, unlike game engines that provide extensive toolsets and editors.

---

# Understanding the Project
Raylib aims to simplify game and graphics programming by offering a streamlined API. It does not come with an extensive GUI but provides low-level access to graphics programming, allowing full control over rendering and game mechanics.

## Key Components
•⁠  ⁠*Core Module*: Manages window, input handling, and time control.
•⁠  ⁠*Graphics Module*: Provides rendering functionalities like textures, shaders, and lighting.
•⁠  ⁠*Audio Module*: Handles sound and music playback.
•⁠  ⁠*Physics Module*: Offers basic physics integration (optional third-party physics engines can be used).

---

# Header and Source Files Overview

## raylib.h
This is the main header file of the Raylib library. It includes function declarations for core functionalities like window management, input handling, texture loading, drawing shapes, and more.

## raymath.h
Provides a collection of useful mathematical functions, including vector and matrix operations, commonly used in game development and graphics programming.

## rgestures.h
Handles gesture recognition for touch-based devices. It provides functions for detecting gestures like swipes, taps, pinches, and drags, enhancing interactivity in mobile applications.

## rshapes.c / rshapes.h
Manages 2D shape drawing functions. Includes support for rendering basic primitives such as lines, rectangles, circles, and polygons. It provides efficient rendering utilities for simple graphical elements in games and applications.

## rmodels.c / rmodels.h
Handles 3D model loading and manipulation. Includes functions for loading models from files, applying transformations, animating models, and rendering 3D objects efficiently.

## rtextures.c / rtextures.h
Manages texture loading and manipulation. Includes functions for loading images, generating textures, applying texture filtering, and rendering textured objects.

---

# Data Structures and Trade-offs

## Data Structures Used
•⁠  ⁠*Arrays*: Store simple data collections, such as vertices and textures. Fast access, but fixed size.
•⁠  ⁠*Linked Lists*: Used for managing dynamic objects like active game entities. More flexible but slower than arrays.
•⁠  ⁠*Structs*: Define objects like ⁠ Vector2 ⁠ (for positions) and ⁠ Rectangle ⁠ (for collisions). Lightweight and efficient.
•⁠  ⁠*Hash Tables*: Store and retrieve assets like textures and sounds quickly. Fast lookup but requires extra memory.

## Trade-offs Explained

•⁠  ⁠*C Language*
  - ✅ Fast and efficient
  - ❌ Requires manual memory management

•⁠  ⁠*Simple API*
  - ✅ Easy to learn and use
  - ❌ Lacks advanced features found in game engines

•⁠  ⁠*No Built-in Game Engine Features*
  - ✅ More flexibility for custom implementations
  - ❌ Requires extra development effort

•⁠  ⁠*Cross-Platform Support*
  - ✅ Runs on multiple operating systems
  - ❌ Some platform-specific adjustments may be needed

---

# Conclusion
Raylib is a powerful yet simple library for 2D/3D graphics programming. It provides the essential tools for building multimedia applications without the complexity of traditional game engines. If you want full control over your project while keeping dependencies minimal, Raylib is an excellent choice.

For more details, visit the [official Raylib website](https://www.raylib.com).
