# Online Retail Data Analysis & Predictive Modeling 

This repository contains a Jupyter Notebook (`hhhhhhh (5).ipynb`) that performs end-to-end data processing and regression analysis on the Online Retail dataset.

##  Project Overview

This project focuses on extracting actionable insights from e-commerce transaction data. The pipeline includes data acquisition via Kaggle, preprocessing, feature engineering, and the training of a regression model to predict key metrics within the retail domain.

## Pipeline Stages

1. **Data Acquisition**: Automatically downloads the latest version of the Online Retail dataset using `kagglehub`.
2. **Data Preparation**: Cleans and structures the transaction data for modeling.
3. **Modeling**: Implements a regression model to estimate continuous variables based on historical sales data.
4. **Evaluation**: Assesses model performance using standard regression metrics.

##  Model Performance

The current regression model has been evaluated using the following metrics:

* **Mean Absolute Error (MAE)**: 3.5949
* **Root Mean Squared Error (RMSE)**: 4.4642
* **R² Score**: 0.1299



##  Technologies Used

* **Python**: Core programming environment.
* **Pandas & NumPy**: For data manipulation and numerical calculations.
* **Scikit-Learn**: For regression modeling and performance evaluation (MAE, RMSE, R2).
* **Kagglehub**: For seamless dataset integration.

## How to Use

1. **Environment Setup**: Ensure you have the necessary libraries installed:
   ```bash
   pip install pandas numpy scikit-learn kagglehub
