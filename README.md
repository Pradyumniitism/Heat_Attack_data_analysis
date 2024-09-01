
## Heart Attack Dataset Analysis

### Summary

This project focuses on analyzing a heart attack dataset to gain insights into various factors related to heart health, such as age, blood pressure, cholesterol levels, smoking status, diabetes status, gender, chest pain type, and treatment outcomes. The analysis includes data loading, preprocessing, and exploratory data analysis (EDA) to uncover trends and correlations.

### 1. Data Loading and Initial Inspection

- **Data Loading:** The dataset was successfully loaded, and initial checks were conducted.
- **Initial Inspection:** This step involved examining the first few rows, dataset shape, data types, missing values, descriptive statistics, duplicated rows, and correlations between variables.
- **Assumptions:** The dataset is assumed to contain various features relevant to heart health, including `Age`, `Blood Pressure`, `Cholesterol`, `Smoking Status`, `Has Diabetes`, `Gender`, `Chest Pain Type`, and `Treatment Outcomes`.

### 2. Data Preprocessing

- **Encoding Categorical Features:** 
  - Categorical features like `Has Diabetes`, `Smoking Status`, `Gender`, `Chest Pain Type`, and `Treatment` were encoded using LabelEncoder for better analysis and model compatibility.
  
- **Feature Engineering:**
  - **Binning Age:** The `Age` column was segmented into five age groups: 30-39, 40-49, 50-59, 60-69, and 70-79.
  - **Binning Blood Pressure:** The `Blood Pressure` column was categorized into five groups: Normal, Pre-Hypertension, Hypertension Stage 1, Hypertension Stage 2, and Hypertensive Crisis.
  - **Binning Cholesterol:** The `Cholesterol` column was categorized into two groups: Normal and High.
  
- **Dropping Original Columns:** 
  - After creating the binned categories for `Blood Pressure` and `Cholesterol`, the original continuous columns were dropped to reduce redundancy.

### 3. Exploratory Data Analysis (EDA)

- **Age Distribution:**
  - A histogram with a Kernel Density Estimate (KDE) was plotted to visualize the age distribution in the dataset.

- **Blood Pressure Categories Distribution:**
  - A count plot was used to display the distribution of blood pressure categories, showing how many individuals fell into each category.

- **Cholesterol Categories Distribution:**
  - A count plot was used to illustrate the distribution of cholesterol categories.

- **Heart Disease by Smoking Status and Diabetes:**
  - A count plot was generated to explore the relationship between `Smoking Status` and `Has Diabetes` in relation to heart disease.

- **Correlation Heatmap:**
  - A heatmap was plotted to visualize correlations between numerical variables, helping to identify potential relationships between features.

### Conclusion

This project provides a comprehensive analysis of heart attack data, focusing on key aspects of heart health. By preprocessing the data and conducting thorough EDA, the analysis uncovers important insights that can be used for further model development and research.
