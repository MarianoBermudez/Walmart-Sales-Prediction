# Walmart Sales Prediction

## Introduction
The objective of this project is to forecast the weekly sales of Walmart stores based on various features utilizing Machine Learning models in Python.

## Project Overview
The main components of the project are:
- Data Visualization
- Feature Engineering
- Machine Learning Models
- Forecasting

## Project Structure
The project has been divided into two files:
1. **Preprocess**: The data is analyzed in a general way, considering that there are multiple stores in the given dataset. New CSV files are generated to focus the analysis and training of the models.
2. **Main**: The data from a specific store is visualized and processed to train the models and provide a forecast. This file can be used to analyze and predict weekly sales for any Walmart store from the Walmart dataset and even the "mean" store data generated previously.

## Dataset
The data contains the following columns:
- Store: Store number
- Date: Sales week start date
- Weekly_Sales: Sales
- Holiday_Flag: Mark on the presence or absence of a holiday
- Temperature: Air temperature in the region
- Fuel_Price: Fuel cost in the region
- CPI: Consumer price index
- Unemployment: Unemployment rate


Dataset link: [Walmart Sales Dataset](https://www.kaggle.com/datasets/mikhail1681/walmart-sales)

## Libraries and Tools
The project utilizes the following libraries and tools:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
