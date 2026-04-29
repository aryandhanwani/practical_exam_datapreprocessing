# 📊 Customer Purchase Behavior Analyzer

## 📌 Overview
This project focuses on analyzing customer purchase behavior by combining multiple datasets and performing data preprocessing. The goal is to clean, transform, and prepare the data for further analysis or machine learning.

---

## 📂 Datasets Used
- CSV file (customer-related data)
- JSON file (additional user information)
- SQL database (product data)

All datasets were merged using common keys like `user_id` and `product_id`.

---

## 🧹 Data Cleaning
- Handled missing values using mean, median, and mode
- Fixed inconsistent entries (e.g., text formats, categories)
- Converted data types where required
- Removed extra spaces and standardized categorical values

---

## 📉 Outlier Handling
Outliers were detected using:
- **Z-score method** → No major impact
- **IQR method** → Removed some records and was more effective

---

## ⚙️ Feature Engineering
- Applied One-Hot Encoding for categorical variables
- Created new transformed features:
  - Log transformation
  - Square root transformation
- These helped in reducing skewness

---

## 📏 Data Scaling
- Used **Min-Max Scaling** to normalize numerical values
- All values were scaled between 0 and 1

---

## 🔗 Data Integration
- Merged CSV, JSON, and SQL datasets
- Used **outer join** to keep all data
- Final dataset contains combined information from all sources

---

## 📊 Final Dataset
- Cleaned and structured data
- Missing values handled
- Outliers reduced
- New features added
- Ready for analysis or ML models

---

## 🧠 Key Learnings
- Importance of cleaning real-world data
- Difference between Z-score and IQR methods
- Handling skewed data using transformations
- Merging multiple data sources effectively
- Preparing data for machine learning

---

## 🚀 Conclusion
The dataset was successfully cleaned, transformed, and merged. After preprocessing, the data is consistent and ready for further analysis or predictive modeling.

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- SQLite
- ydata-profiling

---
