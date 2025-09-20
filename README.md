# Real Estate Linear Regression 🏡📈

This repository contains three projects focused on applying **Linear Regression** methods to predict real estate prices based on features such as surface area and location (city/countryside).

---

## 📂 Projects Included

### 1. Simple Linear Regression
- Dataset: Price vs Surface Area
- Implemented **y = ax + b** model.
- Steps:
  - Data preparation.
  - Visualization: scatter plot + regression line.
  - Cost function calculation.
  - Gradient descent for optimization.
- **Result:** Cost reduced after **normalization**.

---

### 2. Matrix Approach
- Dataset: Price vs Surface Area
- Implemented linear regression using **matrix operations** (no iterations).
- Steps:
  - Data cleaning (missing values replaced by mean, type conversion).
  - Added bias column with `np.hstack`.
  - Computed parameters `theta` with matrix multiplication.
  - Calculated cost function.
- **Result:** Initial cost very high → optimized later with gradient descent.

---

### 3. Multiple Linear Regression + Interface
- Dataset: Price vs Surface Area + Sector.
- Implemented **multiple linear regression**.
- Steps:
  - Data cleaning + categorical encoding.
  - Normalization to prevent overflow.
  - Predictions separated by sector (City vs Countryside).
  - Developed **Tkinter GUI** for user-friendly price estimation.
- **Result:**  
  - Price increases with surface area.  
  - City properties are systematically more expensive than countryside ones.  

---

## ⚙️ Technologies Used
- **Python** (Numpy, Pandas, Matplotlib, Tkinter)
- **Jupyter Notebook**
- **Excel/CSV datasets**

---

## 📌 Notes
These projects show the **evolution from simple to more complex models**:
1. Simple linear regression
2. Matrix approach
3. Multiple linear regression with a GUI

---

### 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/raniabls/real-estate-linear-regression.git
