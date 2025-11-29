# Automatic Number Plate Recognition (ANPR)

**Project type:** Proof-of-concept / research prototype  
**Tech stack:** Python, OpenCV, EasyOCR, NumPy, Matplotlib

---

## 1. Project summary
A simple Automatic Number Plate Recognition (ANPR) prototype that:
- Detects rectangular contours likely to be license plates,
- Crops the candidate plate region,
- Reads text using EasyOCR.

This repository contains the converted Colab notebook code in `anpr.py` (or `anpr.ipynb`) plus sample images.

---

## 2. Requirements
Install dependencies:
```bash
pip install -r requirements.txt
