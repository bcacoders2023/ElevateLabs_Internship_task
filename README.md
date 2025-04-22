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

## 📊 Steps Followed

1. **Handled Missing Values**  
   - Used `.isnull()` to detect missing values  
   - Used `.fillna()` to replace missing values with median/mean where appropriate

2. **Removed Duplicates**  
   - Used `.drop_duplicates()` to remove repeated records

3. **Standardized Text Values**  
   - Converted all text to lowercase  
   - Trimmed leading/trailing whitespaces

4. **Converted Date Formats**  
   - Used `pd.to_datetime()` to ensure consistent `dd-mm-yyyy` format

5. **Cleaned Column Headers**  
   - Renamed columns to lowercase and removed special characters

6. **Corrected Data Types**  
   - Converted numerical and date columns to proper data types using `astype()` and `pd.to_datetime()`

---

## ❓ Interview Q&A

1. **What are missing values and how do you handle them?**  
   Use `.isnull()` to find them. Use `.dropna()` to remove or `.fillna()` to replace them with average, median, etc.

2. **How do you treat duplicate records?**  
   Use `.drop_duplicates()` in Pandas or the "Remove Duplicates" feature in Excel.

3. **Difference between dropna() and fillna()?**  
   - `dropna()` removes missing data.  
   - `fillna()` fills missing data with a specified value.

4. **What is outlier treatment and why is it important?**  
   It removes extreme values that affect analysis. Use IQR, z-score, or capping methods.

5. **Explain the process of standardizing data.**  
   Format text consistently, fix date formats, and normalize categories.

6. **How do you handle inconsistent data formats (e.g., date/time)?**  
   Use `pd.to_datetime()` in Python to convert to a uniform format.

7. **Common data cleaning challenges?**  
   - Inconsistent formatting  
   - Missing/duplicate data  
   - Wrong data types  
   - Outliers

8. **How do you check data quality?**  
   - Use `.info()` and `.describe()`  
   - Visualize with heatmaps  
   - Check unique values and valid ranges

---

# 📊 Task 2: Power BI Data Visualization and Storytelling

## 📌 Objective
Create visualizations using the **Sample Superstore** dataset to find and present key insights for better business decision-making.

## 🔧 Tools Used
- Power BI Desktop
- Sample Superstore Dataset (CSV)

## 📁 Dataset Description
Key columns include:
- Order Date
- Sales
- Profit
- Discount
- Category / Sub-Category
- Segment
- Region
- Customer Name

---

## 📈 Visualizations Created

### 1. **Profit vs Discount Analysis**
- **Chart:** Scatter Plot  
- **X-axis:** Discount  
- **Y-axis:** Profit  
- **Details:** Sub-Category  
- **Insight:** High discounts often lead to lower or negative profits.

### 2. **Sales by Segment and Region**
- **Chart:** Stacked Bar / TreeMap  
- **Group:** Segment and Region  
- **Values:** Sales  
- **Insight:** Consumer segment dominates across most regions.

### 3. **Monthly Sales Trend**
- **Chart:** Line Chart  
- **Axis:** Order Date (Month/Year)  
- **Values:** Sales  
- **Insight:** Sales increase during year-end, showing seasonal peaks.

### 4. **Category-wise Sales and Profit**
- **Chart:** Bar Chart  
- **Axis:** Category / Sub-Category  
- **Values:** Sales & Profit  
- **Insight:** Technology has the highest profit margin; Furniture often has low profit.

---

## 🎯 Key Business Insights
- Excessive discounts hurt profit.
- The Consumer segment performs best across all regions.
- November and December show the highest sales.
- Technology category contributes most to overall profit.

---

## 📎 Deliverables
- Power BI Dashboard (PBIX file or screenshots)
- Cleaned Superstore dataset
- PDF summary report
- This README file

---

## 🧠 Outcome
- Gained hands-on experience with real-world data cleaning.
- Built interactive dashboards using Power BI.
- Learned to draw business insights from visuals.
- Improved storytelling skills using charts and graphs.
![image](https://github.com/user-attachments/assets/b6519b5e-640f-49ae-ae73-686f9badecd5)
![image](https://github.com/user-attachments/assets/83f733e1-347d-4e8e-bd3f-3c3ef2b4c8eb)
![image](https://github.com/user-attachments/assets/12ea28a0-d459-4b19-aa55-7d11124134c2)



## 👤 Author
**Yogesh Kumar Soni**  
BCA Student | Data Analyst Trainee  
🌐 [Portfolio Website](https://yogeshkumarsonicom.netlify.app/)
