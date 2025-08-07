# Task 1: Exploratory Data Analysis (EDA)

## Objective

Perform basic EDA and visualizations on the **Iris Dataset** to understand relationships between features and species.

---

## Dataset

- Source: [Kaggle - Iris Dataset](https://www.kaggle.com/datasets/himanshunakrani/iris-dataset)
- Features: Sepal length, Sepal width, Petal length, Petal width
- Classes: Setosa, Versicolor, Virginica


## Steps Performed

1. **Dataset Loading & Preprocessing**
   - Loaded dataset using Pandas
   - Checked null values and data types
   - Converted target column to categorical if needed

2. **Data Exploration**
   - Checked basic statistics using `.describe()`

3. **Visualization**
   - Histograms & Boxplots to explore feature distributions
   - Heatmap to show feature correlation


## Key Insights

- Petal length and width are the strongest predictors of species.
- Setosa class is clearly separable from others.
- Features are normally distributed with a few minor outliers.


## Notebook: `Task1.ipynb`
