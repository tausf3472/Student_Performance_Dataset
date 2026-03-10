# Student Performance Analysis 📊🎓

## Overview
This project is an exploratory data analysis (EDA) of student performance in secondary education (high school). Using Python, Pandas, and Seaborn, this Jupyter Notebook analyzes demographic factors, study habits, and their correlation with students' final grades. 

## Dataset
The project uses the **Student Performance Dataset** (typically sourced from the UCI Machine Learning Repository). It includes two datasets:
* `student-mat.csv` (Math course performance)
* `student-por.csv` (Portuguese language course performance)

*Note: The data files use semicolons (`;`) as column separators.*

## Technologies Used
* **Python 3.x**
* **Jupyter Notebook**
* **Pandas** (Data manipulation and cleaning)
* **Matplotlib & Seaborn** (Data visualization)

## Project Steps

### 1. Data Loading
* Imported the CSV files into Pandas DataFrames using the custom `sep=';'` parameter to parse the data correctly.

### 2. Data Cleaning & Exploration
* Inspected dataset shapes and data types (`.dtypes`, `.shape`).
* Checked for missing/null values (`.isnull().sum()`).
* Removed duplicate records to ensure data integrity.

### 3. Key Analysis Questions Answered
The notebook calculates specific metrics to answer the following questions:
* What is the average final grade (`G3`) across the class?
* How many top-performing students scored above a 15?
* Is there a measurable correlation between weekly study time and final academic performance?
* How does average performance compare between male and female students?

### 4. Visualizations
The analysis is supported by multiple visualizations:
* **Histogram:** Distribution of final grades (G3).
* **Scatterplot/Stripplot:** The relationship between study time categories and final grades.
* **Bar Chart:** Comparison of average final scores broken down by gender.
