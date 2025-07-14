# ✍️ Handwritten Digit Prediction

This project was developed as part of my internship with **YBI Foundation** on **August 16, 2024**. The goal is to predict handwritten digits using machine learning techniques, specifically the `RandomForestClassifier`. The dataset used is the classic **Digits** dataset from `sklearn.datasets`.

---

## 📌 Project Overview

This notebook performs the following steps:

1. Imports the required libraries
2. Loads and visualizes digit images
3. Preprocesses the data (flattening and scaling)
4. Splits the data into training and testing sets
5. Trains a Random Forest Classifier
6. Predicts test data
7. Evaluates the model using accuracy, confusion matrix, and classification report

---

## 🔍 Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `sklearn.datasets`
- `sklearn.model_selection`
- `sklearn.ensemble`
- `sklearn.metrics`

---

## 📊 Dataset

We use the built-in `digits` dataset from scikit-learn:
- Total samples: 1797
- Image size: 8x8 grayscale pixels
- Features per sample (after flattening): 64

---

## 📈 Model Used

- **RandomForestClassifier** from `sklearn.ensemble`

---

## ✅ Model Accuracy

After training and testing, we achieved:

- **Overall Accuracy**: `97%`
- High precision, recall, and F1-score across all 10 digit classes (0-9)

---

## 🔧 How to Run

1. Clone the repository or download the `.ipynb` file.
2. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Run all cells to train the model and view results.

---

## 📌 Output Example

- **Confusion Matrix**:
[[38 0 0 0 1 0 0 0 0 0]
[ 0 32 0 0 0 0 0 0 0 0]
...
[ 0 0 0 1 0 1 0 0 0 35]]


- **Classification Report**:
accuracy 0.97
precision, recall, f1-score ≈ 0.97 for all digits


---

## 📅 Internship Info

- **Internship**: YBI Foundation
- **Date Completed**: August 16, 2024
- **Project Title**: Handwritten Digit Prediction using Machine Learning

---

## 💡 Author

**Narapureddi Uday Kumar**  
📧 [udayreddi28@gmail.com](mailto:udayreddi28@gmail.com)

---

## 🏷️ Tags

`#MachineLearning` `#DigitRecognition` `#RandomForest` `#YBIFoundation` `#Python` `#ScikitLearn` `#HandwrittenDigits`

---

## 📎 License

This project is part of my learning journey and for educational purposes. Feel free to fork and build upon it! 😊

