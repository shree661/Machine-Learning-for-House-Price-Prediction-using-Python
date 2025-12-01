# Machine-Learning-for-House-Price-Prediction-using-Python
This repository contains a Python-based data analytics notebook that performs **exploratory data analysis (EDA)**, **data cleaning**, **feature engineering**, and **machine learning modeling** on a housing dataset.

The notebook demonstrates a complete workflow from raw CSV input to regression modeling using scikit-learn.

---

## 📁 Project Structure

---

## 🚀 Key Features

### ✅ 1. Data Loading & Inspection
- Reads the housing dataset (CSV format)
- Displays shape, summary statistics, and data types
- Identifies missing values, outliers, and irrelevant columns

---

### ✅ 2. Exploratory Data Analysis (EDA)
The notebook performs:
- Statistical summary (`df.describe()`)
- Info and datatype review (`df.info()`)
- Understanding distributions and correlations  
- Initial interpretation of numerical and categorical variables  

---

### ✅ 3. Data Cleaning
Includes essential preprocessing steps:
- Dropping non-useful columns (e.g., `id`)
- Handling missing values  
- Renaming or reformatting inconsistent fields  
- Feature selection for modeling  

---

### ✅ 4. Feature Engineering
The notebook adds additional transformations such as:
- Polynomial feature expansion  
- Feature scaling  
- Splitting data into train & test sets  

These steps prepare the dataset for improved model performance.

---

### ✅ 5. Machine Learning Models
The notebook uses scikit-learn to train models such as:

- Linear Regression  
- Polynomial Regression  
- Feature scaling via `StandardScaler`  
- Model evaluation metrics  

This end-to-end pipeline shows how preprocessing affects model accuracy.

---

## 🧰 Dependencies

Install all required libraries using:

```bash
pip install pandas numpy scikit-learn


