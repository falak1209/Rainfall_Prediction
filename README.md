# Rainfall_Prediction
## 📌 Project Overview

This project predicts the amount of rainfall based on historical weather conditions using the Linear Regression algorithm. The workflow covers the complete machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, visualization, and prediction.

The project is implemented in Python using Jupyter lab and demonstrates how weather-related features can be used to estimate future rainfall.

---

## 🎯 Objective

To build a machine learning model that predicts rainfall (PrecipitationSumInches) using historical weather data such as temperature, humidity, pressure, wind speed, and dew point.

---

## 📂 Dataset

**Dataset:** Austin Weather Dataset

The dataset contains daily weather observations, including:

- Temperature
- Dew Point
- Humidity
- Sea Level Pressure
- Visibility
- Wind Speed
- Maximum Wind Speed
- Date
- Events
- Precipitation (Target Variable)

Target Variable:

**PrecipitationSumInches**

---

## 🛠️ Technologies Used

- Python
- Jupyter lab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Project Workflow

### 1. Data Loading

- Imported the Austin weather dataset.
- Loaded the dataset using Pandas.

### 2. Data Exploration

- Examined dataset shape.
- Displayed sample records.
- Checked data types.
- Explored dataset structure.

### 3. Data Cleaning

- Checked missing values.
- Replaced invalid symbols.
- Converted the Date column into datetime format.
- Removed unnecessary columns.
- Converted categorical values into numeric format.
- Filled missing values.

### 4. Exploratory Data Analysis (EDA)

Performed visual analysis using:

- Correlation Heatmap
- Rainfall Distribution
- Temperature vs Rainfall
- Humidity vs Rainfall
- Wind Speed vs Rainfall

These visualizations helped understand relationships between weather features and rainfall.

### 5. Feature Selection

Input Features:

- Temperature
- Humidity
- Pressure
- Visibility
- Wind Speed
- Dew Point
- Other weather-related numerical attributes

Target Feature:

- PrecipitationSumInches

### 6. Train-Test Split

- Split the dataset into training and testing sets.
- Used Scikit-learn's train_test_split() function.

### 7. Model Building

Algorithm Used:

**Linear Regression**

The model was trained using historical weather data to predict rainfall values.

### 8. Model Evaluation

The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 9. Visualization

Generated plots for:

- Actual vs Predicted Rainfall
- Residual Analysis
- Feature Importance using Linear Regression Coefficients

### 10. Prediction

The trained model can predict rainfall for new weather observations by providing weather feature values as input.

---

## 📈 Machine Learning Algorithm

**Linear Regression**

Linear Regression is a supervised machine learning algorithm used for predicting continuous numerical values. In this project, it estimates rainfall based on multiple weather parameters.
