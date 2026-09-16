<h1 align="center">🩸 Blood Donation Prediction using Machine Learning</h1>

<p align="center">
  An end-to-end Machine Learning classification project to predict whether a donor is likely to donate blood in the next donation cycle.
</p>

---

## 📌 Project Overview

This project focuses on predicting whether a blood donor will donate blood during the next visit of a mobile blood donation vehicle.

The dataset is based on blood donation records collected from a mobile blood donation vehicle in Taiwan. The prediction task uses a limited set of donor history attributes to identify potential repeat donors.

---

## 🎯 Objective

To build and evaluate Machine Learning classification models that can predict whether a donor will make a blood donation in March 2007.

**Target Variable:**
- `1` – Donated blood
- `0` – Did not donate blood

---

## 📊 Dataset Features

| Feature | Description |
|---|---|
| Months since Last Donation | Number of months since the donor's most recent donation |
| Number of Donations | Total number of donations made by the donor |
| Total Volume Donated | Total volume of blood donated in cubic centimeters |
| Months since First Donation | Number of months since the donor's first donation |
| Made Donation in March 2007 | Target variable indicating whether the donor donated |

---

## 🔄 Project Workflow

1. **Data Loading** – Loaded the blood donation dataset.
2. **Data Understanding** – Examined dataset structure, data types, and target distribution.
3. **Exploratory Data Analysis** – Analyzed feature distributions and relationships.
4. **Data Preprocessing** – Prepared the data for machine learning.
5. **Feature Scaling** – Applied scaling where required.
6. **Model Building** – Trained multiple classification algorithms.
7. **Model Evaluation** – Compared models using relevant classification metrics.
8. **Model Selection** – Selected the final model based on the project objective and evaluation results.

---

## 🛠️ Tech Stack

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook

---

## 📁 Repository Contents

- `Blood Donation Prediction.ipynb` – Complete project notebook
- `Warm_Up_Predict_Blood_Donations_-_Training_Data.csv` – Dataset used for the project

---

## 📌 Disclaimer

This project is developed for educational and machine learning practice purposes. Predictions should not be used as a substitute for professional medical or healthcare decision-making.
