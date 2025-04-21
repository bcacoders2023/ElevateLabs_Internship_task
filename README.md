
# 🧹 Task 1: Data Cleaning and Preprocessing
## 📌 Objective
Clean and prepare a raw dataset by handling:
- Missing values
- Duplicate records
- Inconsistent formatting and data type
## 🛠️ Tools Used

- **Python (Pandas)**  
- **Microsoft Excel**

## 📁 Deliverables

- A **cleaned dataset**
- A **short summary of changes** made during the cleaning process


## 🧠 Hints / Mini Guide

To complete this task, follow these common data cleaning steps:

1. **Handle Missing Values**  
   Use `.isnull()` in Pandas or filters in Excel to identify and handle missing data.

2. **Remove Duplicates**  
   Use `.drop_duplicates()` in Pandas or the "Remove Duplicates" feature in Excel.

3. **Standardize Text Values**  
   Clean columns like gender, country names, etc., to ensure consistency.

4. **Convert Date Formats**  
   Ensure all date columns use a consistent format like `dd-mm-yyyy`.

5. **Clean Column Headers**  
   Rename columns to be lowercase, with no spaces or special characters.

6. **Correct Data Types**  
   Make sure each column has the correct data type (e.g., age → `int`, dates → `datetime`).


## 📊 Recommended Datasets from Kaggle

Choose any of the following for this task:

- Customer Personality Analysis  
- Medical Appointment No Shows  
- Mall Customer Segmentation Data  
- Netflix Movies and TV Shows  
- Sales Data

## 🎯 Learning Outcomes

By completing this task, you will:

- Gain practical experience identifying and fixing real-world data issues.
- Learn data cleaning using both Excel and Python.
- Improve your understanding of data preprocessing, a critical step before analysis or modeling.
- Build confidence in handling raw, unstructured data independently.
- Prepare a clean, structured dataset ready for visualization or predictive analytics.


## ❓ Interview Questions and Answers

**1. What are missing values and how do you handle them?**  
Missing values are entries where data is not available. In Pandas, we use `.isnull()` to detect and `dropna()` or `fillna()` to handle them.  
- **dropna()** removes missing rows.  
- **fillna()** replaces missing values with a specified value (mean, median, etc.).

**2. How do you treat duplicate records?**  
We use `.drop_duplicates()` in Pandas or “Remove Duplicates” in Excel to identify and remove duplicated rows, which can distort the accuracy of the dataset.

**3. Difference between dropna() and fillna() in Pandas?**  
- `dropna()` removes rows or columns with null values.  
- `fillna()` fills missing values with a specific value, such as mean, median, mode, or forward/backward fill.

**4. What is outlier treatment and why is it important?**  
Outlier treatment involves identifying and handling values that deviate significantly from other observations. It’s important because outliers can skew analysis and lead to misleading results. Methods include z-score, IQR, or capping techniques.

**5. Explain the process of standardizing data.**  
Standardization means converting data into a consistent format. For example:
- Making all text lowercase
- Removing leading/trailing spaces
- Standardizing date formats
- Normalizing category labels (e.g., "Male", "male", "M" → "male")

**6. How do you handle inconsistent data formats (e.g., date/time)?**  
Use Pandas’ `pd.to_datetime()` to convert all date fields to a consistent format. It ensures uniformity and enables proper sorting and filtering.

**7. What are common data cleaning challenges?**  
- Missing or inconsistent data
- Duplicate entries
- Outliers
- Mixed data types
- Inconsistent labeling (e.g., “USA” vs. “U.S.A.”)
- Hidden formatting issues (extra spaces, invisible characters)

**8. How can you check data quality?**  
- Use `.info()` and `.describe()` to explore data types and summary statistics.  
- Visualize missing data with heatmaps (using Seaborn or missingno).  
- Validate ranges and values for numerical data.  
- Check unique values for categorical features.

