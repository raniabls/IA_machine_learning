# Artificial Intelligence Course Projects 🤖📊

This repository contains multiple projects showcasing the application of **Machine Learning** and **Deep Learning** techniques to real-world problems.

---

## 📂 Projects Overview

### 1️⃣ Real Estate Price Prediction (Linear Regression)
- **Objective:** Predict real estate prices based on surface area and sector (city/countryside).
- **Methods:**
  - Simple Linear Regression
  - Matrix Approach
  - Multiple Linear Regression
- **Steps:**
  - Data cleaning & preprocessing
  - Visualization (scatter plots + regression lines)
  - Cost function calculation
  - Gradient Descent optimization
  - Tkinter GUI for interactive price estimation
- **Key Results:**
  - Prices increase with surface area
  - City properties are more expensive than countryside
- 📄 See reports in `REGRESSION_LINEAIRE`

---

### 2️⃣ Pneumonia Detection (Logistic Regression vs CNN)
- **Objective:** Classify chest X-ray images into **"Normal"** vs **"Pneumonia"**.
- **Image Preprocessing & Feature Extraction:**
  - Renaming & resizing images (500x500)
  - Feature extraction: Gabor filters, DCT, PHOG, Fourier Transform
- **Models:**
  - Logistic Regression (using extracted features)
  - Convolutional Neural Network (**ResNet**, transfer learning)
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score
- **Key Results:**
  - Logistic Regression Accuracy: **95.45%**
  - ResNet Accuracy: **64.29%**
  - Conclusion: Simpler models can outperform deep learning on small/separable datasets
- 📄 See code & report in `REGRESSION_LOGISTIQUE_CNN`

---

## ⚙️ Technologies Used
- **Python** (Numpy, Pandas, Matplotlib, Scikit-learn, TensorFlow/PyTorch, Tkinter)
- **Anaconda / Jupyter Notebook**
- **Excel/CSV datasets**

---

## 🎯 Notes
- These projects highlight the **contrast between simple Machine Learning and advanced Deep Learning models**.  
- They show how **data size, preprocessing, and feature extraction** can impact performance.  
- They also demonstrate how to go from **basic regression models** to **real-world applications** with graphical interfaces and medical image classification.

---

## 📌 Repository Structure
```bash
IA_machine_learning/
│── README.md
│
├── REGRESSION_LINEAIRE/
│   └── 1.regression_lineaire/
│   └── 2.approche_matricielle/
│   └── 3.regression_lineaire_multiple/
│   └── README.md
├── REGRESSION_LOGISTIQUE_CNN/
│   └── 1.preprocessing_and_feature_extraction/
│   └── 2.model_implementation_and_evaluation/
│   └── README.md

---