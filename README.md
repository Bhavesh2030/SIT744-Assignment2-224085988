# SIT744 Assignment 2 — ECG Arrhythmia (MIT-BIH) + Neural Collapse (Layca)
**Author:** Bhavesh Hiraram Choudhary (ID: 224085988) • **Email:** s224085988@deakin.edu.au

This repository contains:
- **Set 1–3:** Fully-connected MLP for MIT-BIH (AAMI N/S/V), training curves, metrics, confusion matrix, UMAP analysis.
- **Set 4 (HD):** Small-CNN + SGD/Adam/simplified Layca on CIFAR-10 with layer-rotation tracking and neural-collapse probes.

**Paper focus:** *Layer rotation: a surprisingly powerful indicator of generalization in deep networks* (Layca).  
**Report:** [`HD_report.pdf`](HD%20report.pdf)

---

## Quick start

```bash
# 1) Create env
python -m venv .venv && source .venv/bin/activate   # on Windows: .venv\Scripts\activate
pip install --upgrade pip

# 2) Install deps
pip install -r requirements.txt

# 3) Launch Notebook
jupyter notebook  # open 224085988_SIT744_assignment2_solution.ipynb
