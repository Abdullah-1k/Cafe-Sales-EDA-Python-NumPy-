# Exploratory Data Analysis with Python and NumPy — Cafe Sales

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) and data cleaning on a dirty retail cafe sales dataset using **Python**, **Pandas**, and **NumPy**.

## 🛠️ Data Cleaning & Preprocessing
Inspected the raw dataset and resolved missing and corrupted (`ERROR`, `UNKNOWN`) entries across all columns until achieving zero missing values:
- **Categorical Imputation:** Cleaned missing values in `Location`, `Payment Method`, and `Item` using mode imputation.
- **Numerical Imputation (NumPy):** Handled missing entries in `Price Per Unit`, `Total Spent`, and `Quantity` using `np.nanmedian()`, `np.nanmean()`, and vectorized array multiplication `np.multiply()`.

## 📊 Key Statistical Summaries (NumPy)
- Computed overall revenue, mean and median transaction values, and standard deviation using NumPy array operations (`np.sum`, `np.mean`, `np.median`, `np.std`).
- Classified high-value orders using `np.nanpercentile()` and `np.where()`.
- Aggregated sales by item category to identify top revenue-generating products.

## 📂 Repository Files
- `Cafe_Sales_EDA_NumPy.ipynb`: Jupyter Notebook with full Python/NumPy code and statistical outputs.
- `cleaned_cafe_sales.csv`: Final cleaned dataset ready for analysis.
- `dirty_cafe_sales.csv`: Original raw dataset.
