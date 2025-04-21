# 🛒 Amazon Product Data Cleaning

This repository contains a Jupyter Notebook that performs data cleaning on an Amazon product dataset. The dataset includes product information such as prices, discounts, ratings, and rating counts.

## 📁 Files

- `TASK 1.ipynb`: The main notebook that performs data cleaning and preprocessing.
- `amazon_cleaned.xlsx`: The cleaned dataset used in the notebook.

## ⚙️ Features of the Notebook

- **Reading Raw Data**: Loads the Amazon dataset using Pandas.
- **Removing Duplicates**: Eliminates duplicate records.
- **Handling Null Values**:
  - Fills missing ratings with `0`.
  - Fills missing rating counts with `'0'`.
- **Data Transformation**:
  - Cleans and converts `discounted_price` and `actual_price` to float.
  - Converts `discount_percentage` to a numeric percentage.
  - Cleans `rating_count` by removing commas and converting to integers.
- **Index Reset**: Ensures the dataframe has a clean index after transformations.

## 🧰 Requirements

- Python 3.x
- Jupyter Notebook
- pandas

Install dependencies via pip:

```bash
pip install pandas
