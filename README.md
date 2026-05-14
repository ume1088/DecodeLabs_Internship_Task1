# DecodeLabs_Internship_Task1

# 🧹 E-Commerce Order Data Cleaning & Validation

## 📌 Project Overview

This project focuses on cleaning, validating, and standardizing an e-commerce orders dataset using Python and Pandas as part of the DecodesLab Data Analytics Virtual Internship.

The objective was to improve dataset consistency, formatting quality, categorical standardization, and numeric precision while maintaining data integrity for further analysis.

---

## 🎯 Objectives

* Inspect dataset structure and quality
* Detect missing values and duplicates
* Standardize inconsistent categorical values
* Normalize text formatting
* Validate numeric columns
* Improve overall dataset consistency
* Export a cleaned dataset for analysis

---

## 🛠️ Technologies Used

* Python
* Pandas
* Jupyter Notebook

---

## 📂 Dataset Information

* Dataset Type: E-Commerce Orders
* Rows: 1200
* Columns: 14

### Key Columns

* OrderID
* Product
* Quantity
* UnitPrice
* TotalPrice
* PaymentMethod
* ReferralSource
* ShippingAddress
* CouponCode

---

## 🔍 Data Inspection Performed

### Dataset Validation

* Verified dataset structure
* Checked column data types
* Inspected categorical values
* Validated numeric columns

### Duplicate Analysis

* No duplicate rows detected
* `OrderID` values were unique

### Missing Value Analysis

* `CouponCode` contained 309 missing values
* These missing values were intentional because not every customer used a coupon
* No imputation or row removal was required

---

## 🧼 Data Cleaning Operations

### 1. Categorical Standardization

* Replaced inconsistent values in `ReferralSource`
* Standardized categories in `PaymentMethod`

### 2. Text Cleaning

Applied:

* `.strip()`
* `.title()`

on:

* `Product`
* `ShippingAddress`
* `ReferralSource`

### 3. Numeric Formatting

Rounded:

* `UnitPrice`
* `TotalPrice`

to 2 decimal places for consistency.

---

## 📋 Change Log

| Change ID | Description                                                                                   | Impact                      | Status   |
| --------- | --------------------------------------------------------------------------------------------- | --------------------------- | -------- |
| CR001     | Replaced 'Referral' in `ReferralSource` with 'Other'                                          | 222 rows standardized       | Resolved |
| CR002     | Replaced 'Online' in `PaymentMethod` with 'Other'                                             | Inconsistent category fixed | Resolved |
| CR003     | Applied title case and strip formatting to `Product`, `ShippingAddress`, and `ReferralSource` | Text standardized           | Resolved |
| CR004     | Rounded `UnitPrice` and `TotalPrice` to 2 decimal places                                      | Numeric precision enforced  | Resolved |

---

## ✅ Final Outcome

After preprocessing:

* Dataset consistency improved
* Text formatting standardized
* Numeric precision normalized
* Categories unified
* Data validated successfully

The cleaned dataset is now ready for further analysis and reporting.

---

## 📁 Files Included

* `Task1.ipynb` → Main Jupyter Notebook
* `cleaned_dataset.csv` → Cleaned dataset
* `README.md` → Project documentation

---

## 🚀 Internship Information

This project was completed as part of the **DecodesLab Data Analytics Virtual Internship**.

---
## 👩‍💻 About the Author

**Ume Habiba**
Data Cleaning Specialist | BS Information Technology Student | Aspiring AI/ML Engineer

Currently focused on:

* Data Cleaning
* Data Analytics
* Python Automation
* Machine Learning Foundations

Actively building real-world projects and practical experience through internships and hands-on learning.

GitHub: https://github.com/ume1088
LinkedIn: www.linkedin.com/in/ume-habiba-88313537b
