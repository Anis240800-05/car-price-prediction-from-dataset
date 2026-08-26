# car-price-prediction-from-dataset
Machine learning regression project for predicting Ford car prices using vehicle specifications and historical data.
# 🚗 Ford Car Price Prediction

A machine learning regression project that predicts the price of used Ford cars based on vehicle characteristics such as model, year, mileage, transmission, fuel type, tax, MPG, and engine size.

## 📌 Project Overview

The goal of this project is to develop a machine learning model capable of predicting the price of a used Ford vehicle from its available features.

The project covers the complete machine learning workflow:

- Data loading
- Data exploration
- Data cleaning
- Exploratory data analysis
- Feature selection
- Categorical encoding
- Feature scaling
- Train-test splitting
- Model training
- Model evaluation
- Regression analysis

## 📊 Dataset

The dataset contains information about used Ford vehicles and their prices.

The main features used in the project are:

| Feature | Description |
|---|---|
| `model` | Ford vehicle model |
| `year` | Year of manufacture |
| `transmission` | Type of transmission |
| `mileage` | Vehicle mileage |
| `fuelType` | Type of fuel |
| `tax` | Vehicle tax |
| `mpg` | Miles per gallon |
| `engineSize` | Engine size |
| `price` | Target variable |

The dataset was obtained from Kaggle.

## 🔎 Exploratory Data Analysis

Several techniques were used to understand the dataset, including:

- Value counts
- Distribution analysis
- Histograms
- Count plots
- Correlation analysis
- Feature-target relationships
- Identification of unusual values and potential outliers

## 🧹 Data Preprocessing

The data was prepared before training the machine learning model.

The preprocessing steps included:

1. Handling data types
2. Checking for missing values
3. Examining unusual values
4. Encoding categorical variables
5. Scaling numerical features where appropriate
6. Separating features from the target variable
7. Splitting the data into training and testing sets

## 🤖 Machine Learning Model

This project uses a regression approach because the target variable, `price`, is continuous.

The model was evaluated using regression metrics including:

- R²
- Adjusted R²



## 📈 Model Performance

The model achieved:

```text
R² Score:          0.89
Adjusted R² Score: 0.89
