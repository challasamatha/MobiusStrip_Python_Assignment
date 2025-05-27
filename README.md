# MobiusStrip_Python_Assignment 

# Möbius Strip 3D Model and Surface Analysis 🌀

This project models a **Möbius Strip** using parametric equations, computes its **surface area** and **edge length** numerically, and displays a 3D plot of the surface — all in **Google Colab** using Python.

## 🔗 Open in Google Colab
Click the link below to run the project instantly in your browser:
https://colab.research.google.com/drive/1Nk_OJ4u9vfQeXyWbUtWF-WF8wE-1NZS1?usp=sharing

---

## ✨ Features

- Uses parametric equations to define a Möbius strip.
- Approximates:
  - ✅ Surface Area (numerical integration)
  - ✅ Edge Length (numerical curve length)
- 3D Visualization using `matplotlib`.

---

## 📌 Parametric Equation Used

For \( u \in [0, 2\pi] \) and \( v \in [-w/2, w/2] \):

\[
\begin{align*}
x(u,v) &= (R + v \cdot \cos(u/2)) \cdot \cos(u) \\
y(u,v) &= (R + v \cdot \cos(u/2)) \cdot \sin(u) \\
z(u,v) &= v \cdot \sin(u/2)
\end{align*}
\]

---

## 🚀 How to Use

1. **Open the Colab link** above.
2. The notebook is split into:
   - 📦 A class: `MobiusStrip`
   - 🔢 Instantiation and Computation
   - 📊 Plotting the surface
3. Run each cell in order (**Shift+Enter**), or click `Runtime → Run all`.

--- 

## 🛠 Dependencies

Colab has all necessary libraries pre-installed:
- `numpy`
- `matplotlib`

If running locally, install them with:
```bash
pip install numpy matplotlib

---

## 📂 File Structure

mobius_strip_colab/
├── MobiusStrip.ipynb     # Google Colab notebook (main code)
└── README.md             # This file

---

## Author 
Mail : samathachowdary2004@gmail.com
GitHub :  challasamatha
