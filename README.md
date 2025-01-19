# hackathon8762
# Term Deposit Prediction

This repository contains a machine learning model for predicting whether a customer will subscribe to a term deposit based on historical marketing campaign data.

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Files](#files)


## Project Overview

This project aims to:

- **Build a predictive model:** Develop a machine learning model that can accurately predict customer subscription to term deposits.
- **Optimize marketing campaigns:** Identify the most promising leads for telephonic marketing campaigns to maximize conversion rates.

## Data

The dataset used in this project is related to direct marketing campaigns of a Portuguese banking institution. It includes information such as customer demographics, campaign details, and the target variable (subscription status).
The datasets are linked namely, train.csv and test.csv.


## Technologies Used
- **Programming Languages**: Python
- **Libraries and Frameworks**:
  - Scikit-learn (for building the machine learning model)
  - Pandas and NumPy (for data manipulation)
  - Matplotlib and Seaborn (for data visualization)
  - Microsoft PowerBi (for dashboard and visualization)

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
- `hackathon8762.ipynb/`: A Jupyter Notebook containing scripts for data preprocessing, model training, and evaluation.
- `test.csv/`: Stores the data used for model predictions.
- `README.md`: The documentation file explaining the project.
- `hackathon8762.csv/`: The output dataset with the predicted 'y' column.
- `hackathon8762.pdf/`: A visualized dashboard of the results created using Power BI.


## Setup Instructions

Follow these steps to set up and run the project:

1. Download the Required Files:

    - Place the train.csv and test.csv files in the same directory.
    - Download the hackathon8762.ipynb notebook script and place it in the same directory as the CSV files.

2. Open the Notebook:

    - Use your preferred Python IDE. This project was developed using Jupyter Notebook.
    - Open the hackathon8762.ipynb file through your IDE, ensuring that the file paths to train.csv and test.csv are correct and that the file names have not been modified.

3. Run the Notebook:

    - Execute the cells in the hackathon8762.ipynb notebook. This will train the model.

4. Make Predictions:

    - The model will automatically predict the values for the test.csv data and append a new column, y, with the results. There is no need to manually add this column.

5. Completion:

    - That’s it! The model is now ready. Thank you for using this project.


Feel free to reach out if you have any questions or suggestions!
