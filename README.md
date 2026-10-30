# Swiggy Data Analysis Using Python

## Project Overview

This project focuses on analyzing Swiggy food delivery data using Python to uncover business insights related to restaurant performance, pricing patterns, customer ratings, and geographic distribution.

The analysis involves data cleaning, preprocessing, exploratory data analysis (EDA), KPI calculation, and data visualization to understand trends and patterns across different cities, states, restaurants, and food categories.

## Dataset Overview

- **Total Records:** 197,430 (before duplicate removal)
- **Records After Cleaning:** 197,403
- **Duplicate Records Removed:** 27
- **Total Features:** 10
- **States Covered:** 28
- **Time Period:** January 2025 – August 2025

### Dataset Features

| Column | Description |
|---|---|
| State | State where the restaurant is located |
| City | City of the restaurant |
| Order Date | Date associated with the order record |
| Restaurant Name | Name of the restaurant |
| Location | Restaurant location or locality |
| Category | Food category |
| Dish Name | Name of the food item |
| Price (INR) | Listed price of the food item |
| Rating | Restaurant/dish rating |
| Rating Count | Number of ratings |

## Tools & Technologies

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib
- **Environment:** Jupyter Notebook
- **Data Source Format:** Excel

## Project Workflow

### 1. Data Loading & Exploration
- Imported the dataset using Pandas.
- Examined dataset dimensions, column names, and data types.
- Used descriptive statistics to understand data distributions.

### 2. Data Cleaning & Preprocessing
- Checked for missing values and duplicate records.
- Removed 27 duplicate records.
- Verified data types and prepared date-related features for analysis.

### 3. Key Performance Indicators (KPIs)

Calculated the following metrics:

- Total Listed Value: ₹5.30 Crore
- Average Rating: 4.34
- Average Listed Price: ₹268.50
- Total Rating Count: 5.59 Million
- Total Records Analyzed: 197,403

### 4. Exploratory Data Analysis & Visualization

The project explores the following business questions:

- **Monthly Sales Trend:** How does the aggregate listed value vary across months?
- **Daily Sales Trend:** Which days of the week have higher aggregate values?
- **Food Category Analysis:** What is the distribution of listed value between vegetarian and non-vegetarian food items?
- **State-wise Analysis:** How does the aggregate listed value vary across different states?
- **Quarterly Performance:** How do aggregate value, average ratings, and record counts vary across quarters?
- **City-wise Analysis:** Which five cities have the highest aggregate listed value?

## Key Findings

- Analyzed records across **28 states** and 28 cities.
- The average rating across the dataset was approximately **4.34**.
- The average listed price was approximately **₹268.50**.
- Vegetarian items accounted for approximately **67.36%** of the aggregate listed value, while non-vegetarian items accounted for approximately **32.64%**.
- Bengaluru recorded the highest aggregate listed value among the cities, followed by Lucknow, Hyderabad, Mumbai, and New Delhi.
- Saturday recorded the highest aggregate listed value among the days of the week.

## Skills Demonstrated

- Python Programming
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Aggregation and Grouping
- Date and Time Feature Engineering
- Statistical Analysis
- Data Visualization
- Business Insights Generation

## Conclusion

This project demonstrates the use of Python for analyzing large-scale food delivery datasets and extracting meaningful business insights. Through data preprocessing, exploratory analysis, KPI calculation, and visualization, the project highlights patterns in pricing, ratings, food categories, and geographic performance.

The analysis provides a practical understanding of how data analytics can support business performance evaluation and data-driven decision-making.

---

**Author:** Vivek Gautam  
**Tools:** Python | Pandas | NumPy | Matplotlib
