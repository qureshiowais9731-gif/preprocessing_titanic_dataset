# 🚢 Titanic Data Preprocessing and Cleaning Workflow

This repository contains a complete Python script demonstrating the essential data cleaning and preprocessing steps required before training a Machine Learning model, using the classic **Titanic Survival Dataset**.

The primary goal of this script is to transform raw, messy data (with missing values, categorical features, and outliers) into a clean, standardized, and numerical format suitable for algorithms.

---

## 🚀 Project Objectives

This project successfully executes the following five core data preprocessing tasks:

1.  **Data Import & Exploration:** Load the dataset and analyze its structure, types, and missing values.
2.  **Handling Missing Values (Imputation):** Fill in missing `Age` (using mean) and `Embarked` (using mode) data points.
3.  **Feature Encoding:** Convert categorical features (`Sex`, `Pclass`, `Embarked`) into numerical format using Binary Mapping and One-Hot Encoding.
4.  **Outlier Handling:** Visualize and remove extreme outliers from the `Fare` feature using the Interquartile Range (IQR) method.
5.  **Standardization:** Scale all numerical features (`Age`, `Fare`, `SibSp`, `Parch`) to a standard distribution (mean=0, standard deviation=1).

---

## 🛠️ Repository Contents

| File Name | Description |
| :--- | :--- |
| `data_preprocessing.py` | The main Python script containing the complete workflow using Pandas and Scikit-learn. |
| `Titanic-Dataset.csv` | The raw input dataset used for cleaning. |
| `README.md` | This documentation file. |

---

## ⚙️ How to Run the Script

### Prerequisites

You need to have Python installed, along with the following libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
