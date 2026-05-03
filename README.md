# 📊 Customer Shopping Behavior Analysis  

## 📌 Project Overview  
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.  

The objective is to uncover insights into:  
- Customer spending patterns  
- Product preferences  
- Subscription behavior  
- Customer segmentation  

These insights help in making **data-driven business decisions**.

---

## 📂 Dataset Summary  

- **Total Rows:** 3,900  
- **Total Columns:** 18  
- **Missing Values:** 37 (Review Rating column)  

### 🔑 Key Features  
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Shopping Behavior:** Discount Applied, Promo Code Used, Previous Purchases, Frequency, Review Rating, Shipping Type  

---

## 🐍 Data Processing (Python)  

- Loaded dataset using **pandas**  
- Performed data exploration using `.info()` and `.describe()`  
- Handled missing values using **median imputation (category-wise)**  
- Standardized column names to **snake_case**  
- Created new features:  
  - `age_group`  
  - `purchase_frequency_days`  
- Removed redundant columns  
- Loaded cleaned dataset into **PostgreSQL**  

---

## 🗄️ SQL Analysis (PostgreSQL)  

Key business questions answered:

1. Revenue by gender  
2. High-spending customers using discounts  
3. Top 5 products by rating  
4. Shipping type vs purchase behavior  
5. Subscriber vs non-subscriber analysis  
6. Discount-dependent products  
7. Customer segmentation (New / Returning / Loyal)  
8. Top products per category  
9. Repeat buyers vs subscription trends  
10. Revenue by age group  

---

## 📊 Power BI Dashboard  

The interactive dashboard provides:

- 📌 Number of Customers: **3.9K**  
- 📌 Average Purchase Amount: **$59.76**  
- 📌 Average Rating: **3.75**  

### Visual Insights:
- Subscription distribution (27% Yes, 73% No)  
- Revenue & Sales by Category  
- Revenue & Sales by Age Group  
- Filters for Gender, Category, Shipping Type  

---

## 💡 Business Recommendations  

- 🚀 Promote subscriptions with exclusive benefits  
- 🎯 Build loyalty programs for repeat customers  
- ⚖️ Optimize discount strategies  
- 🛍️ Highlight best-selling & top-rated products  
- 📈 Target high-value customer segments  

---

## 🧰 Tech Stack  

- **Python (Pandas, NumPy)** – Data Cleaning  
- **PostgreSQL** – Data Analysis  
- **Power BI** – Dashboard & Visualization  

<img width="1455" height="796" alt="image" src="https://github.com/user-attachments/assets/d300af99-1776-40a9-bebc-4b2aff4ca55c" />

