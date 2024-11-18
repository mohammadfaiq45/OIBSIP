# OIBSIP - Oasis Infobyte Internship

Welcome to the **Oasis Infobyte Data Analytics Internship** repository! This repository contains all the tasks and projects completed as part of my internship at Oasis Infobyte.

## About the Internship
As a Data Analytics Intern at Oasis Infobyte, my focus is on developing and enhancing data analysis skills through real-world tasks. Each task in this repository showcases different aspects of data analysis, data visualization, and reporting.

### 📁 Projects
---
## 1: Exploratory Data Analysis (EDA) on Retail Sales

**Description**  
This project involves exploring and analyzing retail sales data to uncover patterns, trends, and insights. The analysis covers customer demographics, purchasing behaviors, product popularity, and time-based purchasing patterns to help the business make informed decisions.

**Key Insights**  
- **Sales Trends**: Identified high sales peaks and variations across different months.
- **Customer Demographics**: Analyzed age and gender distribution among customers.
- **Product Popularity**: Explored most purchased categories based on age and gender groups.
- **Time Patterns**: Observed peak shopping days and time-based purchasing behaviors.

**Technologies Used**  
- Python, Pandas, Matplotlib, Seaborn, Plotly

## 2: Customer Segmentation Analysis

### Description
This project performs customer segmentation analysis for an e-commerce company. The aim is to identify distinct customer segments based on their purchasing behavior and demographics. The insights gained can help the business target each segment with tailored marketing strategies, enhance customer satisfaction, and improve overall business performance.

### Steps
#### i. Data Collection
Collected a dataset containing relevant customer information, including demographics and purchase history, to facilitate segmentation.

#### ii. Data Exploration and Cleaning
- Checked data structure, missing values, and unique values for each column.
- Created a new feature `TotalSpend` to aggregate spending across product categories.
- Ensured data consistency and handled outliers where necessary.

#### iii. Descriptive Statistics
- **Average Purchase Value**: Calculated the mean spend per transaction.
- **Purchase Frequency**: Calculated total and average purchases across different channels (e.g., store, web).
- **Recency Analysis**: Analyzed the days since last purchase to identify recent and dormant customers.

#### iv. Customer Segmentation
Performed customer segmentation using the K-means clustering algorithm:
- **Feature Selection**: Selected relevant features such as `Recency`, `TotalSpend`, and `NumStorePurchases`.
- **Elbow Method**: Used the elbow curve to determine the optimal number of clusters.
- **Clustering**: Segmented customers into four clusters based on behavioral patterns.

#### v. Visualization
- **Total Spend Histogram**: Showed distribution of total spend across customers.
- **Scatter Plot**: Visualized Recency vs. Total Spend for customer clusters.
- **Boxplots**: Showed income distribution and purchase frequency across clusters.
- **Stacked Bar Charts**: Analyzed average spending by product category and purchase channel.
- **Density Plot**: Showed age distribution within each cluster.

### Conclusion
This project illustrates how clustering and customer segmentation can help an e-commerce business better understand and engage with its customer base. By analyzing customer behavior and demographics, the business can create targeted marketing strategies and drive growth.

### Technologies Used
- **Python**: Data processing and analysis
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-Learn**: K-means clustering

## 3: Data Cleaning Project

**Description**  
This project focuses on cleaning a dataset by addressing issues such as missing values, duplicates, standardization, and outliers. The cleaning process involves ensuring data integrity, handling missing data, removing duplicates, standardizing formats, and detecting and managing outliers. The goal is to prepare the data for accurate analysis and modeling.

**Key Insights**  
- **Missing Data Handling**: Addressed missing values by imputing or removing them to ensure data completeness.
- **Duplicate Removal**: Identified and removed duplicate records to maintain data uniqueness and quality.
- **Standardization**: Ensured consistent formatting across categorical and numeric variables for accurate analysis.
- **Outlier Detection**: Identified and managed outliers to prevent them from skewing results and analyses.

Stay tuned for additional projects and updates!

---
