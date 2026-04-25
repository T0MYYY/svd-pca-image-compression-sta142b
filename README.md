# Dimension Reduction Using SVD and PCA — UC Davis STA 142B Project 1

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
