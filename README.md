# Diwali_Sales_Analysis
🎉 Diwali Sales Analysis – Data Analytics Project

A data-driven analysis of customer purchasing behavior during Diwali season using Python, Pandas, NumPy, Matplotlib & Seaborn.

📌 Project Overview

This project analyzes 11,000+ customer sales records from Diwali season to identify buying patterns based on:

Gender

Age Group

State

Marital Status

Occupation

Product Categories

The goal is to extract insights that can help businesses optimize marketing strategies, identify high-value customer segments, and improve sales decisions.

🛠 Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Jupyter Notebook / Google Colab

📂 Dataset

Total Records: 11,251

Total Features: 15

After cleaning: 11,239 valid rows

Key columns include:

User_ID

Gender

Age Group

State

Occupation

Product Category

Orders

Amount

🧹 Data Cleaning & Preprocessing

Steps performed:

✔ Loaded CSV file
df = pd.read_csv('Diwali Sales Data.csv', encoding='unicode_escape')

✔ Removed unwanted columns

Status and unnamed1 dropped due to zero useful values.

✔ Handled null values

Dropped rows with missing Amount values.

✔ Converted data types

Converted Amount to integer for accurate analysis.

✔ Renamed columns (if needed)

Example:

df.rename(columns={'Marital_Status': 'Shaadi'})

🔍 Exploratory Data Analysis (EDA)
1️⃣ Gender-wise Analysis

Female customers purchased more products and generated higher revenue.

Visualization: Countplot + Barplot for total Amount.

2️⃣ Age Group Analysis

Most buyers are from 26–35 years age group, especially females.

This is the strongest customer segment.

3️⃣ State-wise Sales

Top contributing states:

Uttar Pradesh

Maharashtra

Karnataka

4️⃣ Marital Status

Married women have the highest purchasing power.

They contribute the most to total revenue.

5️⃣ Occupation-wise Insights

Top buying occupations:

IT

Healthcare

Aviation

These groups show the highest spending.

6️⃣ Product Category

Top 3 selling categories:

Food

Clothing

Electronics

Most sold products belonged to these categories.

📊 Visualizations

The analysis includes:

Count Plots

Bar Plots

Group-by Aggregations

Top 10 products analysis

State-wise order count

Age vs Gender comparison

Using matplotlib and seaborn.

🧠 Conclusion (Key Business Insights)

✔ Target Segment:
Married women (age 26–35) working in IT, Healthcare, or Aviation.

✔ Top performing regions:
Uttar Pradesh, Maharashtra, Karnataka

✔ Most popular categories:
Food, Clothing, Electronics

✔ Recommendation for marketing:
Focus Diwali promotions on these segments to maximize ROI.

🚀 How to Run

Clone this repository

git clone <your_repo_link>


Install required libraries

pip install numpy pandas matplotlib seaborn


Run the Jupyter Notebook / Colab file.

📎 Author

Vikash Kumar

Python | Data Analysis | SQL

LinkedIn: https://www.linkedin.com/in/vikash-kumar-886149283/

GitHub: [github.com/vikash03042](https://github.com/vikash03042)
