# Task 3: Linear Regression — House Price Prediction

## Objective
The goal of this task is to implement and understand both **Simple** and **Multiple Linear Regression** using the House Price Prediction dataset.

---

## Tools & Libraries
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset
We used a dataset relevant to **house price prediction**. It contains features like area, number of bedrooms, bathrooms, location, etc.

---

## Task Breakdown

### 1. Import and Preprocess Dataset
- Loaded the dataset using Pandas.
- Handled missing values.
- Encoded categorical variables using one-hot encoding.

### 2. Split the Data
- Used `train_test_split()` from `sklearn.model_selection` to split the data (80% training / 20% testing).

### 3. Fit Linear Regression Model
- Trained both **Simple Linear Regression** (with one feature) and **Multiple Linear Regression** (with multiple features) using `LinearRegression` from `sklearn.linear_model`.

### 4. Model Evaluation
- Evaluated the model using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

### 5. Visualizations
- Plotted the regression line for simple linear regression.
- Displayed a coefficient table to understand the effect of each feature.

---

## Project Structure

```bash
├── data/
│   └── house_prices.csv
├── results/
│   ├── metrics.txt
│   └── coefficients.csv
├── linear_regression_task3.ipynb
├── requirements.txt
└── README.md
