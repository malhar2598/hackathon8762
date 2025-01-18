# hackathon8762
# Term Deposit Prediction

This repository contains a machine learning model for predicting whether a customer will subscribe to a term deposit based on historical marketing campaign data.

## Project Overview

This project aims to:

- **Build a predictive model:** Develop a machine learning model that can accurately predict customer subscription to term deposits.
- **Optimize marketing campaigns:** Identify the most promising leads for telephonic marketing campaigns to maximize conversion rates.

## Data

The dataset used in this project is related to direct marketing campaigns of a Portuguese banking institution. It includes information such as customer demographics, campaign details, and the target variable (subscription status).
The datasets are linked namely, train.csv and test.csv.

## Methodology

1. **Data Loading and Preprocessing:**
   - Load the dataset(train.csv) using pandas.
   - Handle missing values.
   - Perform exploratory data analysis (EDA).
   - Encode categorical variables.
   - Split the data into training and testing sets.

2. **Model Training:**
   - Train a machine learning model, Logistic Regression on the training data.
   - Use appropriate preprocessing techniques feature scaling.

3. **Model Evaluation:**
   - Evaluate model performance on the test set using metrics such as accuracy, precision, recall and F1-score.

4. **Model Deployment and Monitoring:**
   - Integrate the trained model into a system for making predictions on new customer data.
   - Upload the test.csv file to test and make predictions of the new dataset.
   - Making sure that all columns of the dataset is exactly the same, as any discrepancy will leads to errors.

## Files

- `train.csv/`: Contains the dataset used to train the model.
- `hackathon8762.ipynb/)`: Contains Jupyter scripts for data preprocessing, model training, and evaluation.
- `test.csv/`: Stores the trained model file.
- `README.md`: This file.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
