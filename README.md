# Machine Learning GUI

A Python desktop application with a graphical interface to train and evaluate machine learning models (classification & regression) using **scikit‑learn** and **Tkinter**.

---

## 🚀 Overview

This project generates a synthetic dataset and lets you interactively train and evaluate different models via a Tkinter GUI. It supports:

- **Classification:**
  - Decision Tree
  - Logistic Regression (linear)
  - Logistic Regression with Polynomial Features
- **Regression:**
  - Polynomial Regression

Results include accuracy, confusion matrices, classification reports, MSE, and R² scores.

---

## 📦 Features

✔ Simple GUI using **Tkinter**  
✔ Synthetic dataset generation  
✔ Train & evaluate multiple ML models  
✔ Supports polynomial models with custom degree  
✔ Shows evaluation metrics in a scrollable text box

---

## 🧠 Models Included

### Classification
- **Decision Tree**
- **Logistic Regression**
- **Polynomial Logistic Regression**

### Regression
- **Polynomial Regression**

These models are trained and tested on synthetic data created with `sklearn.datasets.make_classification`.

---

## 🛠️ Getting Started

### Requirements

Make sure you have Python 3 installed. Then install the necessary libraries:

```bash
pip install numpy pandas scikit-learn
