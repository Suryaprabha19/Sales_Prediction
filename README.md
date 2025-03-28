Car Purchase Prediction using Machine Learning

Project Overview

This project aims to predict car purchase amounts using machine learning based on historical data. The model analyzes key factors such as age, annual salary, and net worth to provide accurate predictions.

Dataset

The dataset contains customer information, including age, salary, credit card debt, net worth, and car purchase amount. Unnecessary columns such as name and email were removed during preprocessing.

Steps to Run the Project

1. Clone the Repository

git clone <repository_url>
cd <repository_name>

2. Install Dependencies

Ensure you have Python installed. Then install the required libraries:

pip install pandas numpy seaborn matplotlib scikit-learn

3. Run the Script

Execute the main script to train and evaluate the model:

python car_purchase_prediction.py

Features

Data Preprocessing: Handling missing values, removing outliers, and feature scaling.

Exploratory Data Analysis: Visualizing correlations and trends in data.

Machine Learning Model: Trains a Linear Regression model to predict car purchase amounts.

Performance Evaluation: Assesses model accuracy using MAE, MSE, and R² score.

Results

The model achieves a high R² score (~0.9999), indicating strong predictive power.

Age, Salary, and Net Worth are key factors influencing car purchases.

Repository Structure

|-- car_purchasing.csv   # Dataset
|-- car_purchase_prediction.py   # Main script
|-- README.md   # Project documentation
