Below is a **clean, professional GitHub `README.md`** version of your content.
You can **directly copy–paste** this into your GitHub repository.

---

# 🏠 Housing Price Prediction using Linear Regression

## 📌 Project Overview

This project implements a **Linear Regression** model to predict **median house prices** using the **California Housing Dataset**.
Since Linear Regression is a **regression algorithm**, the predicted continuous values are later converted into **binary classes (High Price / Low Price)** in order to generate and visualize a **Confusion Matrix** for evaluation purposes.

---

## 📊 Dataset Information

* **Dataset Name:** California Housing Dataset
* **File Name:** `housing.csv`
* **Total Records:** 20,433 rows

### 🔹 Features

* `longitude`
* `latitude`
* `housing_median_age`
* `total_rooms`
* `total_bedrooms`
* `population`
* `households`
* `median_income`
* `ocean_proximity` (categorical)

### 🎯 Target Variable

* `median_house_value`

---

## ⚙️ Methodology

1. Loaded the dataset using **pandas**
2. Removed missing values
3. Applied **one-hot encoding** to the categorical feature `ocean_proximity`
4. Split the dataset into **training and testing sets**
5. Trained a **Linear Regression** model
6. Converted regression outputs into **binary classes** using the **median house value as threshold**
7. Generated and visualized a **Confusion Matrix**

---

## 📈 Model Evaluation

* **Algorithm Used:** Linear Regression
* **Evaluation Technique:** Confusion Matrix (after threshold-based classification)
* **Threshold:** Median house value

### 📌 Classes

* **Low Price**
* **High Price**

The confusion matrix helps analyze how effectively the regression model differentiates between **low-priced** and **high-priced** houses after classification.

---

## 🧰 Libraries Used

* `pandas`
* `numpy`
* `matplotlib`
* `scikit-learn`

---

## 🚀 How to Run the Project

1. Open **Google Colab** or any Python environment
2. Upload the `housing.csv` dataset
3. Run the provided Python script
4. View the model results and **confusion matrix visualization**

---

## 📌 Important Note

Linear Regression is designed for **continuous value prediction**.
The confusion matrix in this project is created by **converting regression predictions into binary classes** purely for **educational and evaluation purposes**.


