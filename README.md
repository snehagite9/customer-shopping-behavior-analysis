# Customer-Shopping-Behavior-Analysis
This project focuses on analyzing customer shopping behavior using a transactional dataset of 3,900 purchases. The objective is to extract meaningful insights about customer preferences, spending habits, and engagement patterns to support data-driven business decision-making.

The project combines Python (data processing), SQL (analysis), and Power BI (visualization) to deliver a complete end-to-end data analytics solution

# 🎯 Objectives
Understand customer purchasing behavior

Identify high-value customers and segments

Analyze impact of discounts and subscriptions

Discover top-performing products

Provide actionable business recommendations

# ❓ Business Problem

A retail company is facing changes in customer purchasing patterns and wants to:

Leverage consumer data to improve customer engagement, increase sales, and optimize marketing strategies.

This project answers:

What factors influence purchase decisions?

Which customers generate the most revenue?

How can retention and loyalty be improved?

# Dataset Description
📁 Dataset Summary

Total Records: 3,900

Total Columns: 18

Missing Values: 37 (Review Rating column)

🔑 Key Features
👤 Customer Information

Age

Gender

Location

Subscription Status

🛒 Purchase Details

Item Purchased

Category

Purchase Amount

Season

Size & Color

📈 Behavioral Data

Discount Applied

Promo Code Used

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

# ⚙️ Tech Stack
Tool	Purpose
Python (Pandas, NumPy)	Data Cleaning & Preprocessing
PostgreSQL	Data Analysis using SQL
Power BI	Data Visualization & Dashboard
Git & GitHub	Version Control & Project Hosting

# 🔧 Data Preparation (Python)
✔️ Steps Performed

Data Loading

Imported dataset using pandas

Initial Exploration

Checked structure using df.info()

Summary statistics using df.describe()

Data Cleaning

Handled missing values in Review Rating using median

Removed redundant columns

Column Standardization

Converted column names to snake_case

Feature Engineering

Created age_group column

Created purchase_frequency_days

Data Validation

Checked data consistency

Verified duplicate or redundant features

Database Integration

Loaded cleaned dataset into PostgreSQL

# 🗄️ Data Analysis (SQL)
🔍 Business Queries Solved

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type vs Purchase Amount

Subscribers vs Non-Subscribers Analysis

Discount-Dependent Products

Customer Segmentation

Top Products per Category

Repeat Buyers vs Subscription Behavior

Revenue by Age Group

# 📊 Power BI Dashboard

An interactive dashboard was built to visualize:

Revenue distribution

Customer segmentation

Product performance

Subscription insights

Shipping behavior

# 📌 Dashboard Features

Filters (Category, Gender, Age Group)

KPI Cards (Revenue, Avg Spend)

Charts (Bar, Pie, Trend Analysis)

# 🔍 Key Insights
💰 Revenue Insights

Female customers contribute slightly higher revenue

Subscribers contribute 45% of total revenue

📦 Shipping Behavior

Express shipping users spend ~12% more per purchase

💳 Subscription Impact

Subscribers spend 68% more than non-subscribers

Higher repeat purchase rate (78%)

🛍️ Product Insights

Top-rated products:

Blouse ⭐⭐⭐⭐⭐

Dress ⭐⭐⭐⭐⭐

Shirt ⭐⭐⭐⭐

🎯 Customer Behavior

Discount users can still be high-value customers

Certain products are highly discount-driven

# 💡 Business Recommendations
🚀 Growth Strategies

Promote subscription programs with exclusive benefits

Target high-value customers with personalized offers

🎯 Marketing Optimization

Focus on high-revenue segments

Use targeted campaigns for express shipping users

🔁 Customer Retention

Introduce loyalty reward programs

Encourage repeat purchases

🏷️ Pricing Strategy

Optimize discount policies

Balance between sales volume and profit margins

📢 Product Strategy

Promote top-rated products in campaigns

Highlight best-selling categories
