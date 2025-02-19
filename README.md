# 📌 Datahut QA Assignment

## 📖 Introduction
This repository contains the **Data Cleaning Task** for the Datahut QA Assignment.  
The dataset provided consisted of **11,000 records and 8 columns** with various inconsistencies, missing values, and formatting errors.  
The objective of this task was to **clean and standardize the dataset** to ensure it is accurate, complete, and ready for analysis.

---

## 🔍 Dataset Issues Identified & Fixes
### ✅ **1. Missing Values**
- **Name:** Missing values replaced with `"Unknown"`
- **Email:** Missing values replaced with `"missing@example.com"`
- **Join Date:** Standardized format to **YYYY-MM-DD**
- **Salary:** Missing values replaced with the **median salary**
- **Department:** Missing values filled using similar employee records

### 📝 **2. Data Formatting & Cleaning**
- **Join Date:** Standardized to **YYYY-MM-DD**
- **Department Names:** Corrected typos & inconsistencies
- **Email Formatting:** Ensured valid email structures
- **Name Fields:** Removed unwanted characters & words

### 🚀 **3. Outlier & Duplicate Handling**
- **Salary Outliers:** Capped within a valid range (**₹20,000 - ₹200,000**)
- **Age Issues:** Records below **18** or above **65** removed
- **Duplicate Records:** Identified and removed to maintain data integrity

---

## 🛠 **Tools & Technologies Used**
- **Python (Pandas, NumPy, Regex)** → Data Cleaning & Processing
- **Google Colab** → Cloud-based Execution
- **WPS Office (Spreadsheet Tool)** → QA Documentation

---

## 🎯 Conclusion  

After implementing the cleaning steps, the dataset is now:  

✅ **Accurate** – Errors & inconsistencies removed  
✅ **Consistent** – Standardized formats & corrections applied  
✅ **Complete** – Missing values handled efficiently  
✅ **Ready for Analysis** – Suitable for further processing & modeling  

