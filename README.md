Salary Data Analysis - Project Summary

This project involves statistical analysis and data cleaning of a salary dataset. The dataset contains names of individuals along with their corresponding monthly incomes.

Dataset Overview:
File Name: Salary Data.csv
Fields:
Name: The name of each person.
Monthly Income ($): Their reported monthly income.
Tasks Performed:
Statistical Summary:
Calculated the mean, median, and mode of the income data.
Determined the 25th, 50th, and 75th percentiles to understand data spread.

Outlier Detection:
Used the Interquartile Range (IQR) method to detect outliers.
Computed the IQR using Q1 (25th percentile) and Q3 (75th percentile).
Defined outliers as data points lying below Q1 - 1.5 * IQR or above Q3 + 1.5 * IQR.
Identified and removed extreme outliers, including unusually high incomes.

Data Cleaning:
Removed identified outliers to create a cleaned version of the dataset.

Data Visualization:
Plotted box plots to visualize income distribution before and after outlier removal.
These plots clearly show the effect of removing extreme values on data distribution.
Tools and Libraries Used:
Pandas (for data manipulation)
NumPy (for numerical operations)
SciPy (for statistical calculations)
Matplotlib and Seaborn (for data visualization)
