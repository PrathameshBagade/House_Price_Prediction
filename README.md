# 🏠 California Housing Price Prediction (from CSV)

This project predicts the **median house value** for California block groups using the classic housing dataset, loaded from a local CSV file.  
It’s a realistic, **end-to-end regression project** that includes **data cleaning**, **feature engineering**, and **model comparison**.

---

## 📌 1. Project Overview & Problem Statement

### 🧩 Problem
Given a set of features for a California housing block (e.g., location, age, income), build a model to accurately predict its **median house value**.

- **Type:** Regression Problem  
- **Dataset:** `1553768847-housing.csv`  
- **Shape:** 10 columns × 20,640 rows  

---

## 🔄 2. Project Workflow

This project follows the **standard Data Science lifecycle**:

### 🗂️ Data Loading
Loaded the dataset using **Pandas**:
```python
data = pd.read_csv("1553768847-housing.csv")
