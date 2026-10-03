# Hotel Cancellation Prediction

## 📌 Project Overview

Hotel Cancellation Prediction is a machine learning project that focuses on predicting whether a hotel booking will be canceled based on booking-related information.

The project follows a sprint-based approach, starting with understanding the dataset and preparing the data for machine learning.

## 🎯 Project Objective

The main objective of this project is to:

* Understand the hotel booking dataset
* Perform data preprocessing
* Handle missing values
* Separate numerical and categorical features
* Encode categorical variables
* Scale numerical variables
* Prepare the dataset for machine learning
* Build a foundation for hotel cancellation prediction

## 🗂️ Dataset

The project uses the **Hotel Booking Demand dataset**, which contains information about hotel reservations and booking characteristics.

The target variable is:

* `is_canceled` — indicates whether a booking was canceled.

## 🔧 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Git & GitHub

## 🧹 Data Preprocessing

The following preprocessing techniques are used:

### Numerical Features

* Missing values are handled using `SimpleImputer`
* Missing numerical values are replaced using the median
* Numerical features are standardized using `StandardScaler`

### Categorical Features

* Missing categorical values are handled using `SimpleImputer`
* Missing categorical values are replaced using the most frequent value
* Categorical features are encoded using `OneHotEncoder`

### ColumnTransformer

`ColumnTransformer` is used to apply different preprocessing steps to numerical and categorical columns.

### Pipeline

Scikit-learn `Pipeline` is used to organize the preprocessing steps in a structured workflow.

## 🚀 Sprint 1

Sprint 1 focuses on **data understanding and preprocessing**.

Completed tasks:

* Dataset loading
* Data inspection
* Missing-value analysis
* Feature and target separation
* Numerical and categorical feature identification
* Train-test split
* Numerical preprocessing
* Categorical preprocessing
* OneHotEncoder implementation
* StandardScaler implementation
* ColumnTransformer implementation
* Pipeline implementation
* Preparation of processed training and testing data

## 📁 Project Structure

```text
Hotel-Cancellation-Prediction/
│
├── Hotel_Cancellation_Prediction_Sprint1.ipynb
├── hotel_bookings_cleaned.csv
└── README.md
```

## 📊 Current Status

**Sprint 1 — Completed ✅**

The dataset has been preprocessed and prepared for the next stage of the machine learning project.

## 🔮 Future Work

The upcoming stages of the project will focus on:

* Machine learning model development
* Model prediction
* Model evaluation
* Model comparison
* Final hotel cancellation prediction

## 👨‍💻 Author

**Giri Sri Harsha Yaramachu**

This project was developed as part of a practical machine learning/data science project.
