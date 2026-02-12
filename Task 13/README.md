## If the Google colab link does not work, use this: [task 13 (Google Colab)](https://colab.research.google.com/drive/1j3mVcy6soRnvDChsYDUx4WTI4yjaHdUk?usp=sharing)

# PCA – Dimensionality Reduction (MNIST)

## 📌 Overview

This project demonstrates **Principal Component Analysis (PCA)** for dimensionality reduction using the **MNIST dataset**.

The goal is to reduce the number of features while preserving maximum variance and compare model performance before and after reduction.

---

## 📂 Dataset

* MNIST handwritten digits dataset
* 60,000 training images
* 10,000 testing images
* Each image: 28 × 28 pixels (flattened to 784 features)

---

## 🛠 Tools Used

* Python
* Scikit-learn
* Matplotlib
* TensorFlow (for MNIST dataset)

---

## 🔍 Steps Performed

1. Loaded MNIST dataset
2. Flattened images (784 features)
3. Scaled features using StandardScaler
4. Applied PCA
5. Reduced dataset to retain 95% variance
6. Trained Logistic Regression on:

   * Original dataset
   * PCA reduced dataset
7. Compared accuracy
8. Plotted explained variance graph

---

## 📊 Results

| Dataset     | Features | Accuracy |
|-------------|----------|----------|
| Original    | 784      | ~93%     |
| PCA Reduced | ~150     | ~91–93%  |

Observation:

* Dimensionality reduced significantly.
* Accuracy slightly decreased.
* Training becomes faster and more efficient.

---

## 📈 Key Learning

* PCA reduces feature dimensions.
* Explained variance helps choose optimal components.
* There is a trade-off between compression and accuracy.

---

## 📎 Conclusion

PCA successfully compresses the dataset while maintaining most of the important information. It helps improve computational efficiency with minimal accuracy loss.

---
