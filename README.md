# Task-5-Exploratory-Data-Analysis
Exploratory Data Analysis on Titanic Dataset for Internship Task 5 

# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Overview
This repository contains **Task 5** of the Data Analyst Internship – Exploratory Data Analysis (EDA) on the Titanic dataset.  
The objective was to explore the dataset visually and statistically to identify patterns, trends, and relationships that could be useful for further analysis or predictive modeling.

---

## 📂 Files in This Repository
- **EDA.ipynb** → Jupyter Notebook with complete EDA code, outputs, and written observations.
- **Report_of_Findings.pdf** → PDF summary of findings and insights from the EDA.
- **Histogram.png** → Age distribution of passengers.
- **Boxplot.png** → Age distribution by survival status.
- **Scatterplot.png** → Relationship between Age and Fare, colored by survival.
- **Heatmap.png** → Correlation matrix of numeric features.
- **titanic.csv** → Raw Titanic dataset.
- **titanic_cleaned.csv** → Cleaned dataset after handling missing values.

---

## 📊 EDA Steps Performed
1. **Data Loading & Inspection**
   - Used `.info()`, `.describe()`, and `.value_counts()` to understand structure and summary statistics.
   - Checked for missing values and data types.

2. **Univariate Analysis**
   - **Histogram**: Age distribution.
   - **Boxplot**: Age distribution grouped by survival status.

3. **Bivariate Analysis**
   - **Scatterplot**: Age vs Fare, differentiated by survival status.

4. **Correlation Analysis**
   - **Heatmap**: Correlation between numeric features.

5. **Observations**
   - Written for each plot, explaining the key insights.

---

## 🗝️ Key Insights
- Most passengers were aged **20–40**.
- Higher survival rates were observed among **females**, **children**, and **first-class passengers**.
- **Fare** shows a positive correlation with survival; **Pclass** is negatively correlated with Fare.
- Age alone is not a strong predictor of survival, but younger passengers had an advantage.
- Passenger class was a strong factor affecting both Fare and survival probability.

---

## 📥 Dataset Source
[Kaggle - Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

## 🛠️ Tools Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

## ✅ Task 5 Deliverables
- **Jupyter Notebook** with EDA code and results.
- **PDF Report of Findings**.
- **All generated plots** saved as PNG files.
- **Dataset** (raw and cleaned) included for reproducibility.

---
