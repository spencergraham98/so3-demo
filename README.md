# SO(3) 1,000,000 Vector Point Cloud Visualization

High-performance WebGL interactive rendering of 1,000,000 3D vectors representing $SO(3)$ rotations.

## 🚀 Live Demo

[View Interactive WebGL Demo](https://spencergraham98.github.io/so3-demo/)

## 📌 Features

- **1,000,000 Point Uniform Volume**: Volumetric sampling ($\sqrt[3]{r}$) generates a dense, perfectly uniform 3D sphere without central clustering.
- **Mobile Optimized**: Custom 3D-to-2D projection pipeline running on GLSL ES 1.0 shaders for zero-latency mobile touch rotation.
- **Cross-Browser Aspect Lock**: Guarantees a perfectly circular 1:1 isometric projection across vertical mobile screens and desktop viewports.
- **Asynchronous Chunk Loading**: Streams vertex buffers in 100,000-point chunks to maintain smooth initial load times.

## 🎮 Controls

- **Desktop**: Click and drag to rotate the point cloud.
- **Mobile**: Touch and drag to rotate in 3D space.
