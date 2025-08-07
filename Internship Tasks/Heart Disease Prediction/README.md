# Task 3: Heart Disease Prediction

## Objective

Build a classification model to predict if a patient has heart disease based on health indicators.


##  Dataset

- Source: [Kaggle - Heart Disease UCI](https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci)
- Features: Age, Sex, Chest Pain, Blood Pressure, Cholesterol, etc.
- Target: 1 (disease) or 0 (no disease)


## ⚙️ Steps Performed

1. **Dataset Loading & Preprocessing**
   - Handled missing values and outliers
   - Converted categorical variables using one-hot encoding
   - Feature scaling

2. **Model Training**
   - Models tried: Logistic Regression, Random Forest, KNN
   - Evaluated using accuracy, precision, recall, F1-score

3. **Visualization**
   - Correlation heatmap
   - ROC Curve
   - Confusion matrix


## Key Results

- Logistic Regression performed best with 86% accuracy.
- Most important features: Chest Pain Type, Thalach, CA, etc.
- ROC AUC Score: 0.91


##  Notebook: `Task3.ipynb`
