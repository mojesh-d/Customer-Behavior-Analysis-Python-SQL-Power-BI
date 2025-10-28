# Customer Behavior analysis Project
# 📘 Project Overview

This project explores customer shopping patterns using transactional data from 3,900 purchases across multiple product categories.
The goal is to uncover insights into spending behavior, product preferences, seasonal trends, and subscription impact to support data-driven marketing and retention strategies.

# 📊 Dataset Summary

Total Records: 3,900
Features: 18

Key Attributes

* 👤 Customer Demographics: Age, Gender, Location, Subscription Status
* 🛒 Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
* 💳 Shopping Behavior: Discount Applied, Promo Code Used, Frequency of Purchases, Review Rating, Shipping Type
* 🧹 Data Preparation (Python)

Performed using Python (Pandas)

Steps:

* Imported and inspected data using df.info() and df.describe()
* Handled null values and corrected data types
* Created new features:
** age_group → categorized age ranges
** purchase_frequency_days → derived from purchase dates
* Integrated with MS SQL Server for further analysis
  
# 🧮 SQL Analysis

Structured queries were written to extract and analyze key business metrics.

Key SQL Insights:
1.Revenue by Gender: Compared total revenue between male and female customers
2.Top Product Categories: Identified highest-revenue categories
3.Top Rated Products: Found top 5 products with the best average review rating
4.Subscription Impact: Compared spending behavior of subscribers vs. non-subscribers
5.Shipping Preference Analysis: Compared average purchase amounts between standard vs. express shipping
6.Discount Utilization: Found products with the highest discount usage
7.Top Products by Category: Top 3 most purchased items per category
8.Customer Segmentation: Categorized customers as new, returning, or loyal based on purchase history
9.Revenue by Age Group: Analyzed spending patterns across age groups
10.Seasonal Trends: Observed purchase behavior across seasons

# 📈 Power BI Dashboard



Designed an interactive Power BI dashboard to visualize:

<img width="1242" height="728" alt="Custmer Behavour Analysis Dasboard" src="https://github.com/user-attachments/assets/283f0049-2623-4e8c-a3da-1073b7a1849d" />

Dashboard Highlights:
Dynamic slicers for gender, subscription, and season
KPI cards for instant business metrics
Clean, business-ready layout with clear insights

# 💡 Business Insights & Recommendations

Based on the analysis:

* Boost Subscriptions: Offer targeted perks to retain subscribers
* Customer Loyalty: Implement rewards for repeat buyers
* Discount Strategy: Optimize discount frequency to maintain profitability
* Product Promotion: Focus campaigns on top-rated, high-revenue items
* Targeted Marketing: Prioritize high-spending demographics and express-shipping users
  
# 🧰 Tools & Technologies

Tool	Purpose
* Python (Pandas)-	Data cleaning and preprocessing
* MS SQL Server	-Query-based data analysis
* Power BI	-Data visualization and dashboarding
* Excel / CSV-	Data import and storage
  
# 🚀 Key Learnings

* Hands-on experience with end-to-end data analysis
* Strengthened skills in ETL (Extract, Transform, Load) workflow
* Built and optimized Power BI dashboards with KPIs
* Derived business insights from raw data using SQL

# 🏁 Conclusion

This project demonstrates how to transform raw retail data into meaningful business insights using a complete analytics pipeline — from Python data cleaning to SQL analysis to Power BI visualization.


# 🔖 Author

Dundangi Mojesh
📧 www.linkedin.com/in/mojesh-dundangi
📍 Data Analyst | SQL | Python | Power BI
