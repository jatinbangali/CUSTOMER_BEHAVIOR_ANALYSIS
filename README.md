# CUSTOMER_BEHAVIOR_ANALYSIS
📌 Project Overview  This project focuses on analyzing customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover actionable insights into spending patterns, customer segmentation, product preferences, and subscription behavior to support data-driven business decisions.
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories.

The goal is to uncover insights into:

Customer spending patterns
Product preferences
Subscription behavior
Customer segmentation

These insights help drive data-informed business decisions.
Dataset Summary
Feature Type	Details
Rows	3,900
Columns	18
Missing Values	37 (Review Rating)
🔑 Key Attributes
Demographics: Age, Gender, Location, Subscription Status
Purchase Info: Item, Category, Amount, Season, Size, Color
Behavior: Discount, Promo Code, Purchase Frequency, Rating, Shipping
Data Processing (Python)

Key steps performed using Pandas:

📥 Data loading and inspection (.info(), .describe())
🧹 Missing value treatment (median imputation by category)
🔤 Column standardization (snake_case naming)
⚙️ Feature engineering:
age_group
purchase_frequency_days
🔍 Data validation and redundancy removal
🗄️ Exported cleaned dataset to PostgreSQL
SQL Analysis (PostgreSQL)

Solved key business problems:

💰 Revenue comparison by gender
🎯 High-spending customers using discounts
⭐ Top-rated products
🚚 Shipping type vs purchase behavior
👥 Subscriber vs non-subscriber analysis
📉 Discount dependency of products
🔄 Customer segmentation (New / Returning / Loyal)
🏆 Top products per category
🔁 Repeat buyers vs subscription trends
👶 Revenue by age groups
Power BI Dashboard

Interactive dashboard includes:

📌 Customer segmentation insights
📌 Revenue distribution
📌 Product performance
📌 Discount impact
📌 Subscription behavior
<img width="1468" height="845" alt="image" src="https://github.com/user-attachments/assets/e0b089e5-f7c1-4fe6-af67-74bdd89c72ab" />

Business Insights
🚀 Promote subscriptions with exclusive benefits
🎯 Build loyalty programs for repeat customers
⚖️ Optimize discount strategies
🛍️ Highlight best-selling & top-rated products
📈 Target high-value customer segments

🧰 Tech Stack
Python – Data cleaning & preprocessing
PostgreSQL – Data analysis
Power BI – Visualization & dashboard

Customer-Shopping-Analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md

Author

Jatin Bangali
📧 Contact: +91-8965034893
