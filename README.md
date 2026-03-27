# Understanding the Kernel Trick in Support Vector Machines

## 📌 Overview

This project demonstrates how different kernel functions affect the performance of Support Vector Machines (SVMs) on non-linear datasets.

The tutorial focuses on comparing:

- Linear kernel
- Polynomial kernel
- Radial Basis Function (RBF) kernel

It also explores how the **γ (gamma)** parameter influences model complexity, showing examples of underfitting and overfitting.

This project was developed as part of an MSc-level assignment on machine learning.

---

## 🎯 Objectives

- Understand the limitations of linear SVMs
- Explain the kernel trick intuitively and practically
- Compare decision boundaries produced by different kernels
- Analyse the effect of hyperparameters such as γ
- Provide a visual and accessible explanation for students

---

## 📊 Dataset

A synthetic dataset is generated using `make_moons` from `scikit-learn`.

This dataset is intentionally non-linear, making it suitable for demonstrating the importance of kernel methods.

---

## 🧠 Methods Used

- Support Vector Machines (SVM)
- Kernel methods:
  - Linear
  - Polynomial
  - Radial Basis Function (RBF)

---

## 💻 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/svm-kernel-tutorial.git
cd svm-kernel-tutorial
