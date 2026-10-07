# 🎓 Student Academic Performance & Risk Prediction

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/code/adarshdubey0123/student-academic-performance-eda-ml)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)

A Data Science and Machine Learning project analyzing academic risk factors across **200 students**. This repository implements Exploratory Data Analysis (EDA) and trains a **Decision Tree Classifier** to accurately classify students into **Low**, **Medium**, and **High** risk tiers.

---

## 📌 Key Highlights & Results

- **Dataset Size:** 200 clean student performance records.
- **Model Trained:** Decision Tree Classifier (`max_depth=3`).
- **Model Accuracy:** **85.00%** on validation test set.
- **Primary Risk Factor:** Attendance Percentage (< 65% attendance strongly correlates with High Risk).

---

## 🔗 Live Kaggle Artifacts

- 📊 **Dataset on Kaggle:** [Student Academic Performance & Risk Dataset](https://www.kaggle.com/datasets/adarshdubey0123/student-academic-performance-and-risk-dataset)
- 📓 **Kaggle Notebook:** [Interactive EDA & Decision Tree Model](https://www.kaggle.com/code/adarshdubey0123/student-academic-performance-eda-ml)

---

## 📂 Repository Structure

```text
.
├── student_data.csv                    # Clean 200-student dataset
├── Student_Academic_Performance.ipynb  # Main Python analysis & ML notebook
└── README.md                           # Documentation page
