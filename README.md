# World Layoffs Data Cleaning & Exploratory Data Analysis (SQL)
##📌 Project Overview
This project focuses on cleaning and analyzing a dataset of worldwide layoffs from 2020 to 2023. Using MySQL, I transformed a messy raw dataset into a clean format and performed Exploratory Data Analysis (EDA) to uncover trends in the global job market during and after the pandemic.

## 📁 Dataset
Source: Kaggle (Layoffs Dataset)

Size: ~2,300 rows

Tools Used: MySQL Workbench

## 🛠️ Project Structure
Data_Cleaning.sql: Contains the full script for cleaning the data.
<img width="1246" height="393" alt="image" src="https://github.com/user-attachments/assets/bf17cb01-b417-479b-b15e-d09fdd087196" />


Removed duplicates using CTEs and ROW_NUMBER().

Standardized inconsistent naming (e.g., "Crypto", "CryptoCurrency").

Formatted date strings into proper DATE objects.

Handled Null and Blank values by cross-referencing with other rows.

Exploratory_Data_Analysis.sql: SQL queries to find insights.

Total layoffs by company, industry, and country.

Rolling total of layoffs by month.
<img width="1248" height="370" alt="image" src="https://github.com/user-attachments/assets/8ead7983-f007-4f8a-a15b-3fa512a3a1ff" />


Top 5 companies with the most layoffs per year using Window Functions.
<img width="1267" height="603" alt="image" src="https://github.com/user-attachments/assets/25c943cf-6dab-49eb-9437-f15c989c17a5" />


## 📈 Key Insights
Most Impacted Industries: Consumer and Retail saw the highest number of layoffs during the peak periods.

Yearly Trends: 2022 and early 2023 showed a significant spike in layoffs compared to 2020.

Top Companies: Large tech giants like Amazon, Google, and Meta led the total number of layoffs, but many startups went 100% out of business (1.0 percentage laid off).
