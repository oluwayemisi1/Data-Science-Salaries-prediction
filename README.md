# Project Overview
This data science project focuses on predicting salaries for data science professionals using machine learning techniques. The goal is to develop accurate and reliable models that can estimate the expected salary for a given set of features such as work_year, experience_level, employment_type, job_title, salary, salary_currency, salary_in_usd, employee_residence, remote_ratio, company_location, company_size.
Understanding the salary trends and factors affecting compensation in the data science field can provide valuable insights for both job seekers and employers. This project aims to empower stakeholders with informed salary expectations and facilitate data-driven salary negotiations.
![money](https://github.com/oluwayemisi1/Data-Science-Salaries-prediction/assets/48946643/e279f7e5-fbbd-4081-a4ad-e3e97d9e719e)


## Table of Contents:
  1. Data Source
  2. Technologies Used
  3. Data Preprocessing
  4. Exploratory Data Analysis (EDA)
  5. Results and Insights
  6. Conclusion

# Data Scource:
The dataset for this project was collected from Kaggle [Data Science Job Salaries Dataset](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023) a reputable platform for data science and machine learning resources. It contains 3755 data samples (rows) and 11 columns, including features such  work_year, experience_level, employment_type, job_title, salary, salary_currency, salary_in_usd, employee_residence, remote_ratio, company_location, company_size.

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

# Predictions 
The salary prediction task used two distinct machine learning models: Random Forest and Neural Network. These models were employed to forecast and estimate salaries based on the available dataset. The Random Forest algorithm, being an ensemble learning technique, leveraged a collection of decision trees to make predictions. On the other hand, the Neural Network, a deep learning approach, employed a network of interconnected layers to capture intricate patterns in the data.

# Results and Insights
The evaluation results revealed that the Random Forest model obtained a Mean Squared Error (MSE) of 3086716515.1023474 and an R-squared value of 0.2181152888657294, showcasing its ability to capture some patterns in the data, though it still had room for improvement. In contrast, the Neural Network model, trained for 100 epochs, demonstrated promising results with a validation mean absolute error (MAE) of 41173.4883, indicating its proficiency in making accurate predictions. The comparison between the two models shows that the Neural Network outperformed the Random Forest in terms of predictive accuracy for the given task.

# Conclusion 
The data science salary prediction model offers valuable insights into compensation trends, empowering job seekers to make informed decisions and enabling employers to set competitive and fair salary ranges. The project demonstrates the potential of machine learning in solving real-world HR challenges.
