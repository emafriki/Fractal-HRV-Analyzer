# FractalApp – HRV Fractal Generator (Sierpiński Triangle & Tetrahedron)

**Author:** Alma Rocío Patiño Chávez  
**Current status:** Research software accompanying the manuscript  
*“Exploring the fractal complexity of cardiac variability in Epilepsy”* (in preparation).

---

## 🧠 Overview

**FractalApp** is a graphical application developed in Python (Tkinter + Matplotlib) that:

- Reads **time-series data** (e.g., R–R intervals) from `.txt`, `.csv`, or `.dat`
- Generates fractal representations using the **Chaos Game**:
  - **Sierpiński Triangle (2D)**
  - **Sierpiński Tetrahedron (3D)**
- Computes the **fractal dimension** using **box-counting**
- Allows generation of:
  - Control-based fractals
  - Patient-based fractals
  - Randomized fractals (for comparison)
- Saves figures (`.png`) and animated 3D rotations (`.gif`)

This tool was designed for research on **fractal complexity of heart rate variability (HRV)**, but can be used for any numerical time series.

---

## 📦 Features

- Load a time series with a single column  
- Automatic normalization and symbolic labeling  
- Chaos Game implementation (2D & 3D)
- Box-counting fractal dimension estimation  
- Export 2D images and 3D animated GIFs  
- Intuitive graphical interface (Tkinter)  
- Provides reproducible analysis for scientific usage  

---

## 🗂️ Project Structure

