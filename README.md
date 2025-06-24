# 📊 Mean-Variance-Standard Deviation Calculator

## Overview

This project is a Python-based statistical analysis tool that calculates the **mean**, **variance**, **standard deviation**, **maximum**, **minimum**, and **sum** of a 3x3 numerical dataset. It leverages **NumPy** for fast and efficient numerical computations.

As a data scientist, developing such tools is critical in automating exploratory data analysis (EDA), quality checks, and understanding data distributions across various dimensions (rows, columns, and overall).

---

## 👨🏽‍💻 Author

**Eniitan Oluwatoyin Shadrack**  
_Data Scientist | Community Health Data Lecturer | Python & Data Enthusiast_  
📫 `oluwatoyin.eniitan2020@gmail.com`

---

## 🔧 Features

- Accepts a list of 9 numeric elements
- Converts the list into a 3x3 NumPy matrix
- Returns a comprehensive dictionary containing:
  - Mean
  - Variance
  - Standard Deviation
  - Maximum
  - Minimum
  - Sum  
Each metric is calculated across:
  - Axis 0 (columns)
  - Axis 1 (rows)
  - Flattened (entire matrix)

---

## 🧪 Example

```python
from mean_var_std import calculate

print(calculate([0, 1, 2, 3, 4, 5, 6, 7, 8]))
