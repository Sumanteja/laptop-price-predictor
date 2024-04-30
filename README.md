# Laptop-Price-Prediction
A collection of machine learning models for predicting laptop prices
# Stock Trend Prediction

This project aims to predict the stock trends of various companies and visualize the predictions along with the actual stock prices.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Details](#Details)
- [Results](#results)


## Introduction

Stock trend prediction is an essential task for investors and traders to make informed decisions about buying, selling, or holding stocks. This project leverages machine learning algorithms to predict stock prices and provides visualizations to analyze the predicted trends.

## Features

- Predict stock prices of various companies.
- Visualize the predicted trends alongside actual stock prices.
- Compare actual and predicted prices with moving averages (MA50, MA100, MA200).
- Customize predictions for different time periods.

## Details
<details>
<summary style="font-size: 20px;">Dependencies</summary>
To install the required Python packages you can use the following command:

```bash
pip install -r requirements.txt
```
</details>

<details>
<summary style="font-size: 20px;">Datasets Reference</summary>
The dataset is about laptops configuration with prices containing 1302 laptops data with 12 columns Company name,type namee, laptop size in (inches), Screen resolution, CPU, RAM, Memory, GP, Operating system, Price in INR. The dataset was collected from Amazon in 2017-18.
</details>

<details>
<summary style="font-size: 20px;">Regressor Model Choices</summary>

- Multiple Linear Regression
- Ridge Regression
- Lasso Regression
- k-Nearest Neighbors (k-NN)
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest
- ExtraTrees
- Adaptive Boost (AdaBoost)
- Gradient
- Extreme Gradient Boost (XGBoost)
- Voting
- Stacking
- Random Forest Regressor Model - Personal Customization
- Voting Regressor Model (Rf+Gradient) - Personal Customization
</details>

<details>
<summary style="font-size: 20px;">Selected Regression Model</summary>

- Random Forest Regressor Model - Personal Customization

```
R2 Score: 88.78 %
Mean Absolute Error: 15.94 %
```
- Voting Regressor Model (Rf+Gradient) - Personal Customization

```
R2 Score: 0.89 ( 89.27 %)
Mean Absolute Error: 0.15 ( 15.37 %)
```
</details>

<details>
<summary style="font-size: 20px;">Price Currency Conversion [Optional]</summary>
This line of code indicates currency conversion of laptop prices from INR to USD (1 Indian Rupee = 0.012 US Dollar). You can customize the currency exchange rate that suits your need.
<br><br>
  
```
st.title(f"\nPrice: {round(predicted_price * 0.012, 2)} USD")
```
</details>

<details>
<summary style="font-size: 20px;">Run <i>app.py</i></summary>
To run the app.py, load the dependecies requirements and use the following command:
<br><br>
  
```
streamlit run app.py
```
✨ Enjoy the demo
</details>

<hr>

## Results
![Laptop-Price-Prediction](images/1.jpg)

