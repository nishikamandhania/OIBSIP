Customer Sales Data Cleaning Project

📌 Project Overview
This project focuses on cleaning and preparing a messy customer sales dataset using Python and Pandas. The objective was to improve data quality, consistency, and reliability for future analysis.

🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook
- VS Code

📂 Dataset Information
- **Original Dataset:** `messy_customer_sales_data.csv`
- **Final Dataset:** `cleaned_customer_sales_data.csv`
- **Final Shape:** 10,031 rows × 12 columns

🧹 Data Cleaning Steps
1. Identified and handled missing values.
2. Converted Age values to numeric format.
3. Removed invalid Age values outside the 0–100 range.
4. Handled Purchase Amount outliers using the IQR method.
5. Filled missing Purchase Amounts using the median.
6. Filled missing Feedback Scores using the median.
7. Converted date columns into datetime format.
8. Converted Phone Numbers into string format.
9. Standardized Gender categories.
10. Cleaned City and Country values.
11. Removed extra spaces from Name and Email columns.
12. Standardized Email formatting to lowercase.
13. Removed duplicate rows.
14. Performed final data validation.
15. Exported the cleaned dataset as a CSV file.

📊 Final Results
- Invalid Age values: 0
- Invalid Feedback Scores: 0
- Purchase Amounts above the IQR upper bound: 0
- Duplicate rows: 0
- Missing values eliminated from all non-identifier/date columns

Missing Customer IDs and Last Purchase Dates were preserved because their values could not be reliably inferred.

🎯 Key Learning Outcomes
- Data preprocessing using Pandas
- Missing value handling
- Outlier detection and treatment
- Data type conversion
- Categorical data standardization
- Duplicate detection and removal
- Data validation and CSV export

📁 Project Files
- `Data_Cleaning_Project.ipynb` — Jupyter Notebook containing the cleaning process
- `cleaned_customer_sales_data.csv` — Final cleaned dataset

👨‍💻 Project Category
Oasis Infobyte Data Analytics Internship — Level 1, Task 3: Data Cleaning
