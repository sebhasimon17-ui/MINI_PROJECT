# MINI_PROJECT
DISEASE RISK PREDICTION

Objective:
To clean, transform, and analyze patient health data using Python and Pandas, and generate useful reports from the processed data.

Data Source:
The dataset was obtained from Kaggle and contains patient health information such as age, BMI, blood pressure, cholesterol, glucose level, lifestyle factors, and disease risk.

ETL Workflow:
Extract: Load the raw CSV dataset using Pandas.
Transform: Clean missing values, check duplicates, remove unnecessary identifiers, and prepare the data for analysis.
Load: Save the cleaned dataset and analysis reports as CSV files in the reports folder.

List of Transformations:
Missing values were identified and replaced with "Unknown" where appropriate. Duplicate records were checked, data was sorted by age, and Patient_ID was excluded from analysis.

Reports Generated:
cleaned_patient_data.csv – Complete cleaned dataset
summary.csv – Statistical summary of numerical columns
risk_report.csv – Patient count by disease-risk category

Challenges Faced:
Handling missing values in categorical columns and deciding which columns were useful for analysis were the main challenges.

Learning Outcomes:
Learned how to perform basic ETL operations using Pandas, handle missing and duplicate data, and generate reports from a cleaned dataset.

Future Improvements:
The project can be improved by adding more visualizations, advanced data analysis, automated validation, and a machine-learning model for disease-risk prediction.

