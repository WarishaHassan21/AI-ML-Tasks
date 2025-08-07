# Task 2: Short-Term Stock Price Prediction

## Objective

Build a machine learning model to predict next-day stock closing prices using historical data.

## Dataset

- Source: Manually downloaded historical stock data (e.g., Yahoo Finance or other public API)
- Features: Date, Open, High, Low, Close, Volume

## Steps Performed

1. **Dataset Loading & Preprocessing**
   - Loaded CSV file into a Pandas DataFrame
   - Converted date column to datetime format and sorted data chronologically
   - Performed feature engineering (e.g., moving averages, percentage changes)


2. **Model Training**
   - Applied both Linear Regression and Random Forest Regressor
   - Split data into training and testing sets
   - Evaluated models using RMSE (Root Mean Squared Error) or MAE (Mean Absolute Error)

3. **Visualization**
   - Plotted actual vs. predicted closing prices
   - Visualized stock trends over time

## Key Results

- **Random Forest** outperformed **Linear Regression** in prediction accuracy.
- Achieved lower RMSE and MAE using ensemble methods.
- Predictions followed short-term price trends reasonably well.

## Notebook

- All code and analysis are available in the notebook: `Task2.ipynb`
