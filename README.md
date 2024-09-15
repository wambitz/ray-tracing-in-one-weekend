# Ray Tracing in One Weekend

This repository contains the source code and examples for the implementation of a basic ray tracer as outlined in the book _"Ray Tracing in One Weekend"_ by Peter Shirley.

## Project Overview

This project is broken down into multiple steps that guide you through building a simple ray tracing engine. The project structure reflects this with separate folders for each major section of the book.

## Project Structure

```
├── 01_Introduction         # Basic introduction and setup for the project
├── 02_OutputAnImage        # Code to output a simple image
└── build                   # Build files and compiled outputs
```

## Table of Contents

### 1. Overview

### 2. Output an Image

- **2.1** The PPM Image Format
- **2.2** Creating an Image File
- **2.3** Adding a Progress Indicator

<!-- ### 3. The vec3 Class

- **3.1** Color Utility Functions

### 4. Rays, a Simple Camera, and Background

- **4.1** The ray Class
- **4.2** Sending Rays Into the Scene

### 5. Adding a Sphere

- **5.1** Ray-Sphere Intersection
- **5.2** Creating Our First Raytraced Image

### 6. Surface Normals and Multiple Objects

- **6.1** Shading with Surface Normals
- **6.2** Simplifying the Ray-Sphere Intersection Code
- **6.3** An Abstraction for Hittable Objects
- **6.4** Front Faces Versus Back Faces
- **6.5** A List of Hittable Objects
- **6.6** Some New C++ Features
- **6.7** Common Constants and Utility Functions
- **6.8** An Interval Class

### 7. Moving Camera Code Into Its Own Class

### 8. Antialiasing

- **8.1** Some Random Number Utilities
- **8.2** Generating Pixels with Multiple Samples

### 9. Diffuse Materials

- **9.1** A Simple Diffuse Material
- **9.2** Limiting the Number of Child Rays
- **9.3** Fixing Shadow Acne
- **9.4** True Lambertian Reflection
- **9.5** Using Gamma Correction for Accurate Color Intensity

### 10. Metal

- **10.1** An Abstract Class for Materials
- **10.2** A Data Structure to Describe Ray-Object Intersections
- **10.3** Modeling Light Scatter and Reflectance
- **10.4** Mirrored Light Reflection
- **10.5** A Scene with Metal Spheres
- **10.6** Fuzzy Reflection

### 11. Dielectrics

- **11.1** Refraction
- **11.2** Snell's Law
- **11.3** Total Internal Reflection
- **11.4** Schlick Approximation
- **11.5** Modeling a Hollow Glass Sphere

### 12. Positionable Camera

- **12.1** Camera Viewing Geometry
- **12.2** Positioning and Orienting the Camera

### 13. Defocus Blur

- **13.1** A Thin Lens Approximation
- **13.2** Generating Sample Rays

### 14. Where Next?

- **14.1** A Final Render
- **14.2** Next Steps
  - **14.2.1** Book 2: Ray Tracing: The Next Week
  - **14.2.2** Book 3: Ray Tracing: The Rest of Your Life
  - **14.2.3** Other Directions

### 15. Acknowledgments

### 16. Citing This Book

- **16.1** Basic Data
- **16.2** Snippets
  - **16.2.1** Markdown
  - **16.2.2** HTML
  - **16.2.3** LaTeX and BibTex
  - **16.2.4** BibLaTeX
  - **16.2.5** IEEE
  - **16.2.6** MLA -->

## Build Instructions

1. Clone the repository:

   ```bash
   git clone git@github.com:wambitz/ray-tracing-in-one-weekend.git
   ```

2. Navigate to the build directory:

   ```bash
   mkdir build
   ```

3. Build with `cmake`:

   ```bash
   cmake -S . -B build
   cmake --build build
   ```

4. View the subprojects detailed `README` for instructions on how to run the binary.

## Dependencies

This project requires the following:

- A C++17 compatible compiler
- CMake 3.10 or higher

## License

This project follows the license terms provided by the original _"Ray Tracing in One Weekend"_ book.
