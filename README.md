# 🚦 Road Traffic Severity Classification (Addis Ababa, 2017–2020)

This project focuses on classifying the severity of road traffic accidents using real-world data collected from Addis Ababa Sub-city police departments between 2017 and 2020. The dataset includes 12,316 accident records with 32 features (after excluding all sensitive data), and the objective is to predict accident severity using machine learning algorithms.

## 📌 Problem Statement

The target variable `Accident_severity` is a **multi-class** classification problem. The goal is to accurately classify accident severity levels using the available features, optimizing for the **weighted F1-score**.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Handle imbalanced data
- Build and evaluate machine learning models
- Optimize performance using feature selection and dimensionality reduction

---

## 📊 Technologies & Libraries Used

- **Python**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `dabl` for automated EDA
- `scikit-learn` for preprocessing, modeling, and evaluation
- `SMOTENC` for imbalanced data handling

---

## 🔍 Exploratory Data Analysis (EDA)

- Conducted automated EDA using `dabl`
- Visualized feature distributions and relationships using `matplotlib` and `seaborn`

---

## 🧹 Data Preprocessing

- Missing values handled using **fillna**
- Categorical encoding using **One Hot Encoding**
- Feature selection using **Chi-Squared test** and `SelectKBest`
- Dimensionality reduction using **PCA**
- Addressed class imbalance with **SMOTENC**

---

## 🤖 Modeling Approach

- **Baseline model:** Random Forest with default parameters
- **Tuned model:** Random Forest with optimized `n_estimators` and `max_depth`
- Evaluated models using **weighted F1-score**

---

## ✅ Evaluation Results

- **Baseline Model:** F1-score evaluated as a reference point
- **Final Model:** Improved performance after tuning and preprocessing steps

---

## 📁 Dataset

- 12,316 instances
- 32 features
- Target: `Accident_severity` (multi-class)

> Note: The dataset was manually recorded and later cleaned. All personally identifiable information was removed during preprocessing.

---

## 🏁 Conclusion

This project demonstrates the effectiveness of data preprocessing, feature selection, and class balancing techniques in improving multi-class classification performance. It also highlights how real-world accident data can be leveraged to improve road safety analysis using ML.

---

## 📬 Feedback or Contributions?

Feel free to open an issue or pull request if you find improvements or suggestions!

