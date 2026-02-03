# Elevate_Lab2

# AI & ML Internship – Task 2  
## Data Cleaning & Missing Value Handling

---

## 📌 Overview
This repository contains the implementation of **Task 2: Data Cleaning & Missing Value Handling** as part of the AI & ML Internship.  
The goal of this task is to preprocess a real-world dataset by identifying, analyzing, and handling missing values to improve data quality for machine learning applications.

---

## 📂 Dataset
- **House Prices Dataset**  
  *(Workflow is also applicable to Medical Appointment No Shows dataset)*

---

## 🎯 Objectives
- Identify missing values in the dataset
- Visualize missing data patterns
- Apply appropriate imputation techniques
- Remove columns with excessive missing values
- Validate dataset quality after cleaning
- Save all outputs for reproducibility

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab  

---

## 🔍 Methodology
The task was completed using a structured and reproducible workflow:

1. Loaded the dataset and examined its structure.
2. Identified missing values using `isnull().sum()`.
3. Visualized missing value distributions using bar charts.
4. Dropped columns having more than 40% missing values.
5. Applied **adaptive numerical imputation**:
   - Mean imputation for normally distributed data
   - Median imputation for skewed data
6. Applied **mode imputation** for categorical features.
7. Validated the dataset to ensure no missing values remained.
8. Compared dataset quality before and after cleaning.
9. Saved cleaned dataset and analysis outputs automatically.

---

## 📁 Project Structure
Task-2-Data-Cleaning/
│
├── data/
│ ├── raw_dataset.csv
│ └── cleaned_dataset.csv
│
├── outputs/
│ ├── missing_values_before.csv
│ ├── missing_values_after.csv
│ ├── missing_plot_before.png
│ └── missing_plot_after.png
│
├── notebook/
│ └── task2_data_cleaning.ipynb
│
├── report.md
└── README.md


---

## 📊 Results
- Successfully handled missing values
- Improved dataset completeness and consistency
- Generated reusable cleaned dataset
- Dataset is now ready for machine learning modeling

---

## 🧠 Key Concepts Learned
- Importance of data quality in ML
- Mean vs Median imputation strategies
- Handling categorical missing values
- Avoiding data leakage during preprocessing


---

## ✅ Conclusion
This task provided hands-on experience with real-world data preprocessing and strengthened foundational skills required for machine learning workflows.


## output
<img width="461" height="282" alt="Image" src="https://github.com/user-attachments/assets/803be5e6-0795-457b-88b9-7da32ac8f142" />
<img width="928" height="645" alt="Image" src="https://github.com/user-attachments/assets/c674f818-2b21-4392-bb90-b21406f8eddc" />
<img width="1276" height="531" alt="Image" src="https://github.com/user-attachments/assets/2237ac1f-5345-42d8-8a00-a9053a8f37a3" />
<img width="829" height="641" alt="Image" src="https://github.com/user-attachments/assets/815d533d-3103-4fa0-b909-34f9404b092d" />
<img width="1330" height="621" alt="Image" src="https://github.com/user-attachments/assets/96c34d5d-9b98-41bb-8b23-4c260c3589a6" />
