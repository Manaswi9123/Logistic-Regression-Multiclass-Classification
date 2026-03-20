# Logistic-Regression-Multiclass-Classification
# 🔢 Multiclass Classification using Logistic Regression

This repository demonstrates how to extend Logistic Regression to handle **Multiclass Classification** tasks. While standard Logistic Regression is designed for binary outcomes, this project explores how the algorithm classifies data into three or more distinct categories.

---

## 🛠️ The Classification Stack
* **Python**: Core logic.
* **Scikit-Learn**: For the `LogisticRegression` model and the **Digits dataset**.
* **Matplotlib & Seaborn**: For visualizing the input data and the **Confusion Matrix**.
* **NumPy**: For array manipulation and numerical analysis.

---

## 🧠 Key Concepts Implemented

### 1. One-Vs-Rest (OvR) Strategy
Since Logistic Regression is natively binary, it handles multiple classes by training one classifier per class against all other classes combined.
* **Example:** To identify the digit `1`, the model treats it as `Class 1` vs `Not Class 1` (which includes 0, 2, 3...9).

### 2. The Digits Dataset
* Utilized the built-in Scikit-Learn **load_digits** dataset.
* Visualized sample images to understand how the computer "sees" hand-written digits as $8 \times 8$ pixel intensity matrices.

### 3. Model Evaluation & Error Analysis
* **Accuracy Score:** Measuring the overall percentage of correct predictions.
* **Confusion Matrix:** A critical tool used to see exactly which classes are being confused (e.g., is the model mistaking a `1` for a `7`?).
* **Heatmaps:** Used Seaborn to make the error patterns visually intuitive.

---

## 📈 Why use Multiclass Classification?
This technique is the foundation for many real-world AI applications:
* **Optical Character Recognition (OCR):** Identifying letters and numbers in images.
* **Image Tagging:** Categorizing photos (e.g., Cat, Dog, Bird, Plane).
* **Sentiment Analysis:** Classifying text as Positive, Neutral, or Negative.



---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git](https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git)
