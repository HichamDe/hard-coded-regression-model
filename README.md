# 📊 Custom Regression Model

Hello everyone! 👋  
This repository contains my **custom-built regression model** using the **normal equation**:

$\theta = (X^T X)^{-1} X^T y$

---

## 🎯 Project Description

This regression model is designed to **predict how much a student will score on the national exam** based on their grades in:

-  🧮 Math
-  🧪 Physics
-  🇫🇷 French

> **Note:** The dataset used for training and testing the model contains **dummy data**, and is only intended for demonstration purposes.

---

## ⚙️ How It Works

-  The model uses **NumPy** for matrix operations.
-  The `fit()` function calculates the optimal parameters using the normal equation.
-  The `predict()` function estimates scores based on the input features.

---

## 🚀 Getting Started

1. Clone the repository
2. Install NumPy (if not already installed)
   ```bash
   pip install numpy
   ```
