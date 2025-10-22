# ☕ Global Coffee & Health Dashboard

This Streamlit app explores the relationship between **coffee consumption** and various **health metrics** such as BMI, heart rate, and sleep hours.  
It allows users to interactively filter data by **age**, **gender**, **country**, and **lifestyle habits (smoking)** to reveal patterns and correlations.


## 🚀 Features

- **Interactive Sidebar Filters**
  - Select age range, gender, countries, and smoking habits.
- **Data Visualization**
  - Scatter plots showing coffee intake vs. BMI and heart rate.
  - Histogram for sleep hours distribution.
  - Bar chart for average coffee intake by country.
- **Statistical Analysis**
  - Pearson correlation coefficients between variables.
  - ANOVA test to compare coffee intake across countries.
- **Summary Insights**
  - Auto-generated interpretation of findings.

## 🧠 Dataset

The app reads from an Excel file named `synthetic_coffee_health_10000.xlsx`.

To use your own dataset:
1. Replace the file path in the code with your uploaded file.
2. Ensure the dataset includes the following columns:
