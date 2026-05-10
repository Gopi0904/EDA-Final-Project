# Credit Risk Data Analysis & Preprocessing Project

## 📌 Project Overview
This project performs complete data preprocessing and feature engineering on a Credit Risk dataset using Python, Pandas, NumPy, and Scikit-learn.

The notebook covers the full data science preprocessing pipeline including:
- Data acquisition
- Data cleaning
- Missing value handling
- Outlier treatment
- Feature engineering
- Feature scaling
- Feature transformation
- Final cleaned dataset generation

---

# 📂 Dataset Files
The project uses:
- `customer_credit_risk_dataset_12000.csv`
- `customer_credit_risk_dataset_12000.json`
- SQLite Database (template included)

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- SQLite
- Jupyter Notebook

---

# 📖 Project Tasks Covered

## Part A — Conceptual Foundation
- What is Data Analysis
- Planning a Data Science Project
- Framing a Machine Learning Problem
- Tensor Explanation with NumPy Examples

---

## Part B — Data Acquisition
- CSV File Loading
- JSON File Parsing
- SQLite Database Querying
- Dummy API Integration Example

---

## Part C — Data Understanding & Cleaning
- Dataset Exploration using:
  - `.info()`
  - `.describe()`
- Pandas Profiling Section
- Missing Value Analysis

### Missing Value Handling Techniques
- Simple Imputer
- Most Frequent Imputation
- Random Sample Imputation
- Missing Indicator
- KNN Imputer
- MICE Algorithm
- Complete Case Analysis

---

## Part D — Outlier Handling
- Z-Score Method
- IQR Method
- Percentile Method
- Winsorization Technique

---

## Part E — Feature Engineering

### Variable Handling
- Date & Time Feature Extraction
- Mixed Variable Processing

### Encoding Techniques
- Ordinal Encoding
- Label Encoding
- One-Hot Encoding

### Numerical Feature Encoding
- Binning
- Binarization
- Quantile Binning
- K-Means Binning

---

## Part F — Feature Scaling
- Standardization
- Normalization
- Min-Max Scaling
- MaxAbs Scaling
- Robust Scaling

---

## Part G — Feature Construction & Transformation

### Transformations
- FunctionTransformer
- Log Transformation
- Reciprocal Transformation
- Square Root Transformation
- PowerTransformer
- Box-Cox Transformation
- Yeo-Johnson Transformation

### ColumnTransformer
- Different preprocessing pipelines for numerical and categorical columns

### New Features Created
- Debt-to-Income Ratio
- Average Monthly Transactions
- Spending-to-Income Ratio

---

## Part H — Final Deliverable
- Final Cleaned Dataset
- Preprocessed Dataset Export
- Final Summary Report

---

# ▶️ How to Run

1. Install required libraries:
```bash
pip install pandas numpy scikit-learn scipy jupyter
```

2. Open Jupyter Notebook:
```bash
jupyter notebook
```

3. Run:
```bash
complete_credit_risk_project.ipynb
```

---

# 📤 Output Files
- Final cleaned dataset CSV
- Preprocessed features
- Feature engineered dataset

---

# 📊 Final Result
The dataset is fully cleaned, transformed, and prepared for Machine Learning model building and predictive analytics.

---

# 👨‍💻 Author
Gopi0904