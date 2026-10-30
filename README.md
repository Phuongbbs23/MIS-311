# MIS-311
Introduction to Business Analytics - 	Becamex Business School
## 1. Data Overview 📊

The selected dataset, **01_Cost of Living**, provides information about average monthly income and cost of living across different countries and geographical regions over time. The dataset contains 199 observations and 5 variables, covering 12 countries across 6 geographical regions from 2000 to 2023.

### Table 1. Dataset Overview

| Description | Details |
|---|---|
| Dataset Name | 01_Cost of Living |
| Total Observations | 199 |
| Total Variables | 5 |
| Number of Countries | 12 |
| Number of Regions | 6 |
| Time Period | 2000–2023 |
| Data Type | Numerical and Categorical |

### Table 2. Description of Variables

| Variable | Data Type | Description |
|---|---|---|
| Country | Categorical | The name of the country. |
| Year | Numerical | The year in which the data was recorded. |
| Average_Monthly_Income | Numerical | The average monthly income recorded for each country and year. |
| Cost_of_Living | Numerical | The recorded cost of living for each country and year. |
| Region | Categorical | The geographical region to which each country belongs. |

### Purpose of the Analysis 🎯

This dataset was selected to examine differences in average monthly income and cost of living across countries and geographical regions. The analysis aims to identify patterns, compare regional differences, and explore the relationship between income levels and living expenses through Exploratory Data Analysis (EDA), descriptive statistics, and data visualisations.
## 2. Data Cleaning 🧹

### 2.1 Missing Values 🔍

The dataset contained four missing values: two in the `Average_Monthly_Income` column and two in the `Region` column. The missing values were handled as follows:

**Table 3. Missing Values Summary**

| Variable | Missing Values | Percentage | Action Taken |
|---|---:|---:|---|
| Average_Monthly_Income | 2 | 1.01% | No action needed |
| Region | 2 | 1.01% | Filled with the correct region |

The missing values in the `Region` column were filled with **"North America"** based on the countries' geographical locations. The missing income values were left blank because the actual values could not be confirmed, avoiding inaccurate data.

### 2.2 Duplicate Records 🔄

The dataset was checked for duplicate records to ensure data consistency and reliability.

**Table 4. Duplicate Records Summary**

| Item | Results |
|---|---:|
| Duplicate Rows Found | 2 |
| Action Needed | Remove |

Two duplicate records were identified and removed using Excel's Remove Duplicates function. This reduced the dataset from **201 to 199 records** and helped prevent duplicate entries from affecting the analysis.

### ✅ Data Cleaning Summary

After completing the data cleaning process:
- Missing values in `Region` were filled with the correct geographical region.
- Missing values in `Average_Monthly_Income` were retained because their actual values could not be verified.
- Two duplicate records were removed.
- The final dataset contained **199 records and 5 variables**.

The cleaned dataset was then used for further descriptive statistical analysis.
## 3. Descriptive Analysis 📊

### 3.1 Income vs. Cost of Living Baseline

Descriptive analytics summarizes raw data to provide a clear understanding of its central trends, overall distribution, and spread.

### Table 5. Descriptive Statistics for Monthly Income and Cost of Living
<img width="875" height="425" alt="image" src="https://github.com/user-attachments/assets/b5af740b-1493-4756-9f77-3aeca8b39ce0" />



### Figure 1. Comparison of Average Monthly Income and Cost of Living
<img width="835" height="486" alt="image" src="https://github.com/user-attachments/assets/2d41757d-3431-4a8c-a87b-f4e8b73d6f18" />


From **Table 5** and **Figure 1**, the average monthly income (4,243.97) is higher than the average cost of living (3,705.13). This means that, on average, people earn enough to cover their basic living expenses with some money left over. However, because both values are close, many individuals might still face financial pressure depending on where they live. Additionally, economic fluctuations like inflation or unexpected expenses can quickly put individuals under financial strain, especially in high-cost regions.


### Figure 2. Comparison of Standard Deviation Income and Cost of Living
<img width="701" height="411" alt="image" src="https://github.com/user-attachments/assets/8a410e62-d12e-41e6-ba6b-2db67c17621f" />


From **Table 5** and **Figure 2**, both average monthly income and cost of living exhibit very high standard deviations, with 2,126.41 and 1,982.22, respectively. This shows that the data points are widely spread out rather than closely clustered around the average. This high variation highlights significant global economic inequality, meaning that national income levels and living costs vary drastically across different countries and regions.

### 3.2 Regional Comparison

### Table 6. Regional Comparison of Average Monthly Income and Cost of Living**
<img width="1003" height="263" alt="image" src="https://github.com/user-attachments/assets/ba2a6110-15d0-48af-96f5-f1fd9e7d81dc" />

### Figure 3. Regional Comparison of Average Monthly Income and Cost of Living
<img width="1018" height="428" alt="image" src="https://github.com/user-attachments/assets/a8147c3b-f42b-473d-b0fb-7d35b820e404" />

Looking across regions, North America has the narrowest difference between income and living expenses (3,764.28 vs. 3,750.07, leaving only a 14.21 surplus), whereas Europe enjoys the largest financial gap, with an average margin of over 922.91. This demonstrates that geographic location significantly impacts net savings potential, meaning individuals in regions like North America face much tighter financial flexibility compared to those in Europe.


## 4. Conclusion 📌

In conclusion, this data analysis highlights significant global economic disparities, showing that while average incomes slightly exceed living costs, high standard deviations reflect vast inequality across countries. Furthermore, regional comparisons indicate that geographic location heavily influences financial stability, with regions like North America experiencing much tighter disposable margins than Europe. Overall, these findings provide a clear understanding of global purchasing power dynamics and underscore the financial vulnerabilities populations face in high-cost environments.
