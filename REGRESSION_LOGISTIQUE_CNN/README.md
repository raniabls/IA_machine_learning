# Pneumonia Detection: Logistic Regression vs. CNN

This repository contains the code and report for a final project for an Artificial Intelligence course. The project compares the performance of two machine learning models—**Logistic Regression** and a **Convolutional Neural Network (ResNet)**—for the binary classification of medical chest X-ray images as either **"Normal"** or **"Pneumonia."**

## 🎯 Project Objective

The main goal of this project was to determine which of the two models, a simpler linear model (Logistic Regression) or a more complex deep learning model (ResNet), would perform better on a specific medical image dataset.

## ⚙️ Methodology

### 1. Image Preprocessing & Feature Extraction

-   All images were renamed to a consistent format.
-   Images were resized to 500x500 pixels.
-   Key features were extracted from the images using various techniques, including:
    -   Gabor filters
    -   Discrete Cosine Transform (DCT)
    -   Pyramid Histogram of Oriented Gradient (PHOG)
    -   Fourier Transform

### 2. Model Implementation & Evaluation

-   **Logistic Regression:** A logistic regression model was trained using the extracted features. The model's performance was evaluated using various metrics, including accuracy, precision, recall, and F1-score.
-   **Convolutional Neural Network (CNN):** A pre-trained ResNet model was used for the classification task. The model's performance was also evaluated using the same metrics for a direct comparison.

## 📊 Results & Conclusion

The final results showed that **Logistic Regression performed significantly better** than the ResNet model on this particular dataset.

-   **Logistic Regression Accuracy:** 95.45%
-   **ResNet Accuracy:** 64.29%

This surprising outcome is attributed to the nature of the dataset. The classes in the images were found to be sufficiently separable with a linear approach, making the simpler Logistic Regression model more effective. The ResNet model, while powerful, likely suffered from the small size of the dataset and required more fine-tuning to perform optimally. The conclusion is that for this specific problem, a simpler, less resource-intensive model was a superior choice.

## 💻 Technologies Used

-   Anaconda
-   Jupyter Notebook