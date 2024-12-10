**Diwali Sales Analysis**
This project provides an exploratory data analysis (EDA) of a Diwali Sales dataset using Python. The objective is to clean the dataset, analyze sales patterns, and visualize key insights to understand customer behavior and sales trends.

Table of Contents
Introduction
Technologies Used
Setup and Installation
Data Cleaning Steps
Exploratory Data Analysis (EDA)
Visualizations
Conclusion

**Introduction**

This project analyzes Diwali sales data to extract meaningful insights and patterns about customers and their buying behavior. The dataset contains information about gender, age, state, occupation, marital status, and purchase details.

The analysis includes:

Data cleaning to remove null and unnecessary values.
Data type conversions and renaming of columns.
Generating descriptive statistics.
Visualizing patterns in customer demographics and sales.
Technologies Used
Python
Pandas for data manipulation and cleaning.
Seaborn and Matplotlib for data visualization.
Jupyter Notebook for analysis and code execution.
Setup and Installation
Clone the repository to your local machine.

**Data Cleaning Steps**

Importing the Data:

Loaded the dataset using pandas.read_csv().
Dropping Unnecessary Columns:

Removed columns like Status and unnamed1 that did not provide useful information.
Handling Missing Values:

Identified null values using pd.isnull() and removed them with dropna().
Changing Data Types:

Converted the Amount column from float to integer using astype().
Renaming Columns:

Renamed columns like Marital_Status to shadi for better clarity.
Exploratory Data Analysis (EDA)
The analysis focused on understanding patterns and relationships in the dataset. Some key EDA steps include:

Count plots to analyze customer distribution by gender, age group, state, and marital status.
Aggregated sales data using groupby() for metrics like total amount and total orders.
Derived insights by comparing sales metrics across demographic groups.
Visualizations
Gender Distribution:
Bar charts comparing the total number of customers and total sales by gender.
Age Group Analysis:
Visualized the relationship between age groups, gender, and total sales.
State-Wise Analysis:
Highlighted top states by total orders and total sales.
Occupation and Product Analysis:
Explored sales trends by occupation and product categories.
Top 10 Products:
Identified the most popular products based on sales and orders.

**Conclusion**

The Diwali Sales Analysis revealed:

Sales are higher among certain age groups and occupations.
Some states contribute significantly more to sales volume and revenue.
Specific product categories and IDs were top performers.
These insights can guide marketing strategies and inventory management for future campaigns.






