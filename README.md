# 🏠🏠 House Price Prediction 🔮🔮
![Python version](https://img.shields.io/badge/Python%20version-3.10%2B-lightgrey)
![GitHub last commit](https://img.shields.io/github/last-commit/Taweilo/house_price_prediction)
![GitHub repo size](https://img.shields.io/github/repo-size/Taweilo/house_price_prediction)
![Type of ML](https://img.shields.io/badge/Type%20of%20ML-Regression%20-red)
![License](https://img.shields.io/badge/License-MIT-green)

Badge [source](https://shields.io/)

 <img src="https://www.bouzaien.com/post/house-pricing-prediction/featured.png" width="1100" height="450">
This project will follow the Business Analysis (BA) workflow to address house price prediction using data mining techniques. The business problem is creating a machine-learning model that can accurately predict house prices based on the provided features. Real estate agents can utilize this model to evaluate the property.

```
├── Image                       
│
├── Code_House_Price_Prediction.ipynb             <- code
├── Housing data.csv                              <- dataset
├── LICENSE                                       <- MIT license
├── README.md                                     <- read me
```

## 1. Business Understanding
The goal of this project is to develop a predictive model for housing prices based on various property attributes, including area, number of bedrooms and bathrooms, etc.

## 2. Data Understanding 
The Diabetes dataset was loaded via Colab. The dataset is from Kaggle: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset (also please see Housing data.csv attached). Basic data analysis was performed to identify the shape of data, get column names, find missing values, and generate descriptive statistics. The pair plot demonstrated the relationship between variables. The distribution of the target class variable was shown.

* Data Dictionary
 
| Name | Modeling Role | Measurement Level| Description |
| ---- | ------------- | ---------------- | ---------- |
| **Price** | target | int | Price of the Houses |
| **Area** | input | int | Area of a House |
| **Bedrooms** | input | int | Number of House Bedrooms |
| **Bathrooms** | input | int | Number of Bathrooms |
| **Stories** | input | int | Number of House Stories |
| **Mainroad** | input |  boolean | Weather connected to Main Road |
| **Guestroom** | input |  boolean | Weather has a guest room |
| **Basement** | input |  boolean  | Weather has a basement |
| **Hotwaterheating** | input |  boolean | Weather has a hot water heater |
| **Airconditioning** | input |  boolean | Weather has an airconditioning |
| **Parking** | input | int | Number of House Parkings |
| **Prefarea** | input |  boolean | Prefarea of the House |
| **Furnishingstatus** | input |  boolean | Furnishing status of the House |


 
## 3. Data Preparation 
1. Define variables (X and y) 
2. Split the data into train and test datasets; 30% of test data <br>
   train: 381 data<br>
   test:  164 data<br>
3. Standardize the data
  
## 4. Modeling   
Several machine learning models were included:
* Linear Regression
* LASSO Regression
* Ridge Regression
* Elastic Net
* Decision Tree Regression
* Support Vector Regression
* K-Nearest Neighbors Regression
* Random Forest Regression
* Gradient Boosting Regression (e.g., XGBoost)
* Neural Network Regression

## 5. Evaluation
<img src="https://github.com/Taweilo/House_Price_Prediction/blob/main/Image/5.%20evaluation%20.png" width="500" >

