# Project Overview
This data science project focuses on predicting salaries for data science professionals using machine learning techniques. The goal is to develop accurate and reliable models that can estimate the expected salary for a given set of features such as work_year, experience_level, employment_type, job_title, salary, salary_currency, salary_in_usd, employee_residence, remote_ratio, company_location, company_size.
Understanding the salary trends and factors affecting compensation in the data science field can provide valuable insights for both job seekers and employers. This project aims to empower stakeholders with informed salary expectations and facilitate data-driven salary negotiations.

## Table of Contents:
  1. Data Source
  2. Technologies Used
  3. Data Preprocessing
  4. Exploratory Data Analysis (EDA)
  5. Feature Engineering
  6. Model Selection
  7. Model Training and Evaluation
  8. Results and Insights
  9. Conclusion
# Data Scource:
The dataset for this project was collected from Kaggle, a reputable platform for data science and machine learning resources. It contains 3755 data samples (rows) and 11 columns, including features such  work_year, experience_level, employment_type, job_title, salary, salary_currency, salary_in_usd, employee_residence, remote_ratio, company_location, company_size.

# Technology used:
  1. Python 3.8
  2. Jupyter Notebook
  3. pandas
  4. NumPy
  5. scikit-learn
  6. seaborn
  7. matplotlib

# Data preprocessing:
  1. Data preprocessing is a critical step in this project. In this project there were no missing value found.
  2. The 'employment_type' column initially contained the values 'FT', 'PT', 'CT', 'FT', 'FL', which was changed to 'Fulltime', 'Part time', 'Contract', 'Fulltime', 'Freelance'.
  3. The 'experience_level' column initially contained the values 'SE', 'MI', 'EN', 'SE', 'EX', twhich was converted to 'Senior', 'Mid Senior', 'Entry', 'Senior', 'Executive'.

# Exploratory Data Analysis (EDA):
  1. I examined the distribution of data science salaries based on different experience levels to gain insights into the variations in compensation across varying levels of professional experience.
  2. I identified the top six most frequent job titles in the dataset, shedding light on the most prevalent roles within the data science domain.
  3. I investigated the distribution of salaries within the dataset, providing a comprehensive view of how salaries are spread across different data science positions.
  4. I computed the average salary for each company location within the dataset TO providE valuable insights into how compensation differs across different geographical areas.
  5. I analyzed the distribution of salaries in USD from the dataset to provide valuable insights into the frequency of various salary ranges.
  6. I did an analysis to calculate the average salary for each unique company location in the dataset to identify potential regions with higher or lower compensation rates for data science positions.
  7. I computed the average yearly salary for data science positions based on different company locations to provide valuable insights for job seekers and employers seeking to understand regional salary trends in the data science field.
  8. I calculated the mean salary for data science positions based on different employment types to provide valuable insights into how employment type influences salary levels within the data science domain.
  9. 

  10. 
