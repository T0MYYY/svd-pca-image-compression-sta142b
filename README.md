# Dimension Reduction Using SVD and PCA — UC Davis STA 142B Project 1

<!-- BADGES_BEGIN -->
<p align="center">
  <img alt="Course" src="https://img.shields.io/badge/Course-STA%20142B-022851?style=flat-square&labelColor=2a323d">
  <img alt="UC Davis" src="https://img.shields.io/badge/UC%20Davis-Statistical%20Learning-FFBF00?style=flat-square&labelColor=2a323d">
  <img alt="Term" src="https://img.shields.io/badge/Term-Spring%202023-2a323d?style=flat-square&labelColor=2a323d">
  <img alt="Author" src="https://img.shields.io/badge/Author-Solo-1f7a3d?style=flat-square&labelColor=2a323d">
  <img alt="Status" src="https://img.shields.io/badge/Status-Submitted-ec5800?style=flat-square&labelColor=2a323d">
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10-3776AB?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-notebook-F37626?style=flat-square&labelColor=2a323d&logo=jupyter&logoColor=white">
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-1.24-013243?style=flat-square&labelColor=2a323d&logo=numpy&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-1.2-F7931E?style=flat-square&labelColor=2a323d&logo=scikitlearn&logoColor=white">
  <img alt="matplotlib" src="https://img.shields.io/badge/matplotlib-3.7-11557C?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
</p>
<!-- BADGES_END -->

Individual project implementing image compression via Singular Value Decomposition (SVD) and dimensionality reduction via Principal Component Analysis (PCA).

**Course:** STA 142B — Statistical Learning (Spring 2023, UC Davis)  
**Author:** Chiyang Chen

---

<p align="center">
  <img src="images/yosemite.png" width="65%">
</p>

---

## Project Overview

| Part | Topic |
|---|---|
| Part 1 | SVD Image Compression — compress a color image at varying rank approximations |
| Part 2 | PCA — dimensionality reduction and variance analysis |

---

## Files

| File | Description |
|---|---|
| `notebook.ipynb` | Full analysis notebook |
| `report.pdf` | Submitted PDF report |
| `images/yosemite.png` | Source image used for SVD compression |
| `images/data.png` | Additional image data |

---

## Key Concepts

- **SVD** — decompose image matrices into rank-k approximations; lower rank = higher compression
- **PCA** — project high-dimensional data onto principal components to capture maximum variance

---

## Libraries

```
numpy · matplotlib · sklearn · PIL
```

---

## How to Run

```bash
jupyter notebook notebook.ipynb
```
