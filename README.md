# 📊 Customer Churn EDA – Phase 1: Data Exploration & Initial Assessment

## 🔹 Project Overview
This project focuses on analyzing **Customer Churn Data** to understand early patterns and potential issues in the dataset.  
Phase 1 involves **Exploration & Initial Assessment** before moving into data cleaning and deeper analysis.  

## 🔹 Dataset Details
- **Rows:** 3,150  
- **Columns:** 14  
- **Target Variable:** `Churn` (0 = Retained, 1 = Churned)  

### Features:
- **Numerical Columns:**  
  `Age`, `Charge Amount`, `Customer Value`, `Seconds of Use`, `Frequency of use`, `Frequency of SMS`,  
  `Distinct Called Numbers`, `Call Failure`, `Subscription Length`  

- **Categorical Columns:**  
  `Complains`, `Age Group`, `Tariff Plan`, `Status`, `Churn`  

## 🔹 Phase 1 Objectives
- Explore dataset structure and understand feature types  
- Compute **descriptive statistics** for numerical columns  
- Identify **missing values** and their distribution  
- Detect **outliers** and unusual patterns  
- Check for **categorical inconsistencies** and value distributions  
- Document **initial observations** and data quality concerns  

## 🔹 Key Findings (Phase 1)
- **Missing Values:** Present in `Customer Value`, `Subscription Length`, `Charge Amount`, and `Call Failure`  
- **Outliers:** Extreme values in `Charge Amount`, `Customer Value`, `Seconds of Use`, and `Frequency of SMS`  
- **Data Types:** Some categorical variables stored as numeric (e.g., `Status`, `Complains`, `Tariff Plan`, `Churn`)  
- **Initial Relationships:**  
  - Higher charges and complaints appeared linked with churn  
  - Usage features showed skewed distributions (few power users dominate usage)  

---

✅ Phase 1 provided a **solid understanding of the dataset** and highlighted the need for **data cleaning, type corrections, and handling outliers**, which were addressed in **Phase 2**.
