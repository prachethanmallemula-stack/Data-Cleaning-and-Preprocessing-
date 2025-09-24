# Data-Cleaning-and-Preprocessing-
Cleaned and prepared the Mall Customers dataset for analysis by removing duplicates, standardizing gender values, renaming columns, and verifying data types. Delivered a clean, structured CSV and Python code for reproducible data preprocessing.

Mall Customers Dataset 

Objective: The goal of this task was to clean and prepare the Mall Customers dataset so it is ready for analysis and modeling.

Steps Performed

	1.	Checked for Missing Values
	•	Used df.isnull().sum() to verify missing data.
	•	No missing values were found.
	
	2.	Removed Duplicate Rows
	•	Applied df.drop_duplicates() to ensure all records were unique.
	
	3.	Standardized Text Values
	•	Cleaned and standardized the Gender column (stripped spaces, converted to proper case: Male / Female).
	
	4.	Renamed Column Headers
	•	Converted all column names to lowercase and replaced spaces with underscores for consistency.
	•	Example: Annual Income (k$) → annual_income_(k$)
	
	5.	Checked & Validated Data Types
	•	Ensured age, annual_income_(k$), and spending_score_(1-100) were integers.
	•	All data types were correct, so no changes were needed.
	
	6.	Date Conversion
	•	No date columns were present in this dataset, so no conversion was required.

Outcome
	•	Produced a clean, structured dataset (mall_customers_cleaned.csv) ready for further analysis.
	•	Ensured data quality by removing duplicates and standardizing formats.
	•	This cleaned dataset can now be safely used for clustering, segmentation, and visualization tasks.
