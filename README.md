# Wine Dataset: EDA and Feature Scaling Pipeline 🍷

An end-to-end exploratory data analysis (EDA) and data preprocessing pipeline built with Python, focusing on feature scaling, normalization, and visualization techniques for machine learning preparation.

---

## 🚀 Project Overview
In machine learning workflows, raw data often contains features with varying scales, which can negatively impact model performance. This project demonstrates how to analyze a wine dataset, visualize distributions, and apply feature scaling techniques using **Scikit-Learn**, **Pandas**, and **Seaborn**.

---

## 🛠️ Tech Stack & Libraries
* **Python** (3.13+)
* **Pandas & NumPy** (Data Manipulation & Numerical Operations)
* **Matplotlib & Seaborn** (Data Visualization & Distribution Plots)
* **Scikit-Learn** (Train-Test Splitting & MinMax/Standard Scaling)
* **Jupyter Notebook** (Interactive Development Environment)

---

## 📊 Key Steps & Features
1. **Data Loading & Inspection:** Loaded `wine_data.csv`, checked null values, data types, and statistical summaries.
2. **Exploratory Data Analysis (EDA):** 
   - Created scatter plots with color mapping (`hue`) based on wine classes.
   - Analyzed Kernel Density Estimation (KDE) plots for features like *Alcohol* and *Malic acid*.
3. **Data Preprocessing & Splitting:** Separated features and labels, splitting the dataset into training and testing sets.
4. **Feature Normalization / Scaling:** Applied `MinMaxScaler` and `StandardScaler` to bring all features into a uniform scale.
5. **Comparative Visualization:** Plotted side-by-side distribution comparisons ("Before Scaling" vs. "After Scaling").

---

## 📂 Repository Structure
```text
├── wine_data.csv          # Dataset file
├── normalization.ipynb    # Jupyter Notebook containing the full code
└── README.md              # Project documentation
