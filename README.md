# Vision Geometry Toolkit

A Rust library for 2D and 3D geometric transformations, tailored for computer vision and robotics applications. It provides a robust, type-safe foundation for working with rotations, poses, and other spatial transformations, enabling precise and efficient algorithm development.

## Key Features
*   Implementations of SO(2), SO(3), SE(2), and SE(3) Lie groups.
*   Type-safe operations for rotations, translations, and poses.
*   Support for automatic differentiation via dual numbers.
*   Interoperability with common linear algebra types.

## Tech Stack
*   **Language:** Rust
*   **Core Dependencies:** `nalgebra`, `num-traits`, `approx`

## Getting Started
Add the library to your `Cargo.toml`:
```toml
[dependencies]
vision-geometry-toolkit = "0.1"
```
Import and use the modules in your code:
```rust
use vision_geometry_toolkit::se3;
```