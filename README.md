# Car Price Prediction (Linear Regression)

## Overview
This project implements a **Linear Regression** model to predict car selling prices based on various vehicle attributes.

---

## Dataset Features
- **Car_Name**: Name of the car  
- **Year**: Manufacturing year of the car  
- **Present_Price**: Current showroom price of the car  
- **Kms_Driven**: Total distance driven by the car (in km)  
- **Fuel_Type**: Type of fuel (Petrol/Diesel)  
- **Seller_Type**: Type of seller (Dealer/Individual)  
- **Transmission**: Transmission type (Manual/Automatic)  
- **Owner**: Number of previous owners  
- **Selling_Price**: Target variable (price at which the car is sold)  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  

---

## Workflow & Steps
1. Load the dataset using Pandas  
2. Inspect data (shape, missing values, duplicates)  
3. Clean data (drop duplicates)  
4. Encode categorical features (`Fuel_Type`, `Seller_Type`, `Transmission`) using LabelEncoder  
5. Split dataset into features (X) and target (y)  
6. Perform 80-20 train-test split  
7. Train the **Linear Regression** model  
8. Evaluate performance using MAE, MSE, and R² Score  

---

## Results & Performance Metrics
- **Mean Absolute Error (MAE):** 1.22  
- **Mean Squared Error (MSE):** 3.53  
- **R² Score:** 0.847 (~84.7% accuracy)  

---
## About
A machine learning project implementing Linear Regression in Python to analyze and predict car prices based on vehicle attributes.
