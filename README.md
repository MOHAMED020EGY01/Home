# Home 3D Scene - Blender Project (Level 1)

A 3D architectural visualization project created in Blender featuring a home scene with realistic lighting and environment.

---

## 📖 Project Description

This project is a Blender 3D scene file showcasing a residential home visualization. It includes realistic lighting setup using HDRI environment mapping and rendered output images suitable for architectural presentations or portfolio work.

**Target Use Cases:**
- Architectural visualization
- Real estate marketing materials
- 3D portfolio showcase
- Lighting and rendering practice

---

## ⚙️ Features

- **Realistic HDRI Lighting** - Uses suburban garden HDRI for natural environment lighting
- **High-Quality Renders** - Pre-rendered images at high resolution (2K)
- **Production-Ready Scene** - Complete with world environment setup
- **Architectural Focus** - Residential home 3D model

---

## 🏗️ Tech Stack

| Category | Technology |
|----------|------------|
| **3D Software** | Blender (.blend file format) |
| **Lighting** | HDRI Environment Mapping (EXR) |
| **Output** | PNG (lossless compression) |
| **Environment Map** | suburban_garden_2k.exr |

---

## 📁 Project Structure

```
Home/
├── Home.blend              # Main Blender scene file
├── HomeImage_1.png         # Rendered image 1
├── HomeImage_2.png         # Rendered image 2
└── World/
    └── suburban_garden_2k.exr   # HDRI environment lighting map
```

| File/Folder | Description |
|-------------|-------------|
| `Home.blend` | Main Blender project file containing 3D models, materials, camera, and lighting setup |
| `HomeImage_*.png` | Final rendered output images (3840x2160 estimated) |
| `World/suburban_garden_2k.exr` | 2K HDRI environment map for realistic outdoor lighting |

---

## 🚀 Usage Guide

### Requirements

- **Blender 3.0+** (recommended for full compatibility)
- **Disk Space:** ~50 MB for project files
- **RAM:** 8GB+ recommended for opening and rendering

### Opening the Project

1. Install [Blender](https://www.blender.org/download/) (latest stable version)
2. Clone or download this repository
3. Open `Home.blend` in Blender:
   ```bash
   blender Home.blend
   ```
   Or double-click the file (if Blender is set as default)

### Working with the Scene

- **Camera:** Pre-positioned for optimal viewing angle
- **Lighting:** HDRI world lighting already configured
- **Render Engine:** Likely uses Cycles or Eevee (check in Blender's Render Properties)

### Re-rendering Images

1. Open `Home.blend`
2. Go to **Render > Render Image** (F12)
3. Save the output: **Image > Save As** (Alt+S)

---

## 🧠 Scene Architecture

### Lighting Setup
- **Type:** HDRI Environment Lighting
- **Source:** `suburban_garden_2k.exr`
- **Placement:** World shader background
- **Effect:** Provides natural outdoor illumination with realistic shadows and reflections

### Render Outputs
- **Format:** PNG (lossless)
- **Files:** 
  - `HomeImage_1.png` - Primary view render
  - `HomeImage_2.png` - Secondary/alternative view render

---

## 📝 Notes

- The `.exr` file is a high-dynamic-range image used for realistic lighting
- PNG renders are already provided for quick preview without opening Blender
- Scene may contain mesh objects, materials, and camera animation data (inspect `.blend` file to verify)

---

## 👨‍💻 Credits

- **HDRI Environment:** suburban_garden_2k.exr (source not specified in project)
- **Scene Author:** Not specified in codebase
- **Software:** Blender Foundation

---

## 📦 File Sizes

| File | Size |
|------|------|
| Home.blend | ~568 KB |
| HomeImage_1.png | ~1.6 MB |
| HomeImage_2.png | ~1.9 MB |
| suburban_garden_2k.exr | ~23.2 MB |

---

## 🔗 Related Resources

- [Courses Video YouTube](https://www.youtube.com/watch?v=40pOGqcH4qg&list=PLVFmIR_nrKU4oX3PnaQyKrGMz3gOXEd5B&index=14)

- [Polyhaven HDRI Library](https://polyhaven.com/hdris)
