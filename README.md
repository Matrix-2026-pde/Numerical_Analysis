# Numerical Analysis

My journey through computational mathematics. This repository contains Python implementations of numerical methods, accompanied by LaTeX reports and numerical stability analyses.

## 📂 Projects

### 1. Linear Systems
- **LU Decomposition (Partial Pivoting)**
  - Implementation of LU decomposition with and without partial pivoting.
  - Demonstrates the crucial difference between matrix conditioning (ill-conditioned vs well-conditioned) and algorithmic stability.
  - *Files:* [`LU.py`](./01_Linear_Systems/LU.py), [`Report`](./01_Linear_Systems/finish.pdf)
  - *Key Result:* Well-conditioned matrix can still produce catastrophic errors without pivoting, achieving relative error ~1e-16 with pivoting.

## 🛠️ Tech Stack
- Python (NumPy, Matplotlib)
- LaTeX
