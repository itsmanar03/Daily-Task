# Breast Cancer Classification using Ensemble Learning 🧬

This repository contains a **Jupyter Notebook** (`main.ipynb`) that demonstrates how to classify breast cancer tumors as either **Malignant** or **Benign** using various **Ensemble Learning** techniques.

## 🛠️ Libraries Used
The project is built using the following Python libraries:
* **Scikit-learn**: Used for loading the dataset, splitting the data, and calculating accuracy.
* **XGBoost**: Used to implement the high-performance Extreme Gradient Boosting algorithm.

## 📊 Dataset
The notebook uses the **Breast Cancer Wisconsin (Diagnostic) Dataset** provided by `sklearn`.
* **Features**: 30 numeric attributes describing the characteristics of cell nuclei.
* **Target**: Binary classification (Malignant or Benign).
* **Data Split**: 80% of the data is used for training, and 20% is reserved for testing.

## 🤖 Models & Methodology
We implemented and compared three powerful **Boosting** algorithms:

1.  **Gradient Boosting Classifier**: An ensemble technique that builds trees sequentially to minimize errors.
2.  **AdaBoost (Adaptive Boosting)**: A model that focuses on correcting the mistakes of previous weak learners.
3.  **XGBoost Classifier**: An optimized, scalable version of gradient boosting designed for efficiency.

## 📈 Final Results
The models achieved the following **Accuracy Scores** on the test set:

| Model | Accuracy |
| :--- | :--- |
| **AdaBoost** | **97.37%** |
| **Gradient Boosting** | **95.61%** |
| **XGBoost** | **95.61%** |
