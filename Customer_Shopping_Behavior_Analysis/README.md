# 🛒 Customer Shopping Behavior Analysis
### End-to-End Data Analyst Project | Python • SQL • Power BI

---
![](/dhasboard_image.png)

## 📌 Project Overview
This project analyzes **3,900 customer shopping transactions** to uncover insights into customer behavior, spending patterns, product performance, and subscription impact to support business decision-making.

---

## 🔗 Live Dashboard Link / File
🔗 [Live Dashboard](https://app.powerbi.com/groups/me/reports/7f66a95e-8689-4fbf-8711-240a3db3b103/42badd025db1ee5e79a4?experience=power-bi)

### Dashboard File
You can find the file for the dashboard here: [`customer_shopping_dashboard.pbix`](customer_shopping_dashboard.pbix). 


---


## 📂 Dataset Details
- Rows: 3,900
- Columns: 18
- Includes demographics, purchase details, and behavioral data
- Missing values handled using statistical imputation

---

## 🔽 Data Cleaning & Feature Engineering (Python)

- Loaded dataset using pandas  
- Handled missing Review Ratings using median per product category  
- Standardized column names (snake_case)  
- Removed redundant columns  
- Created:
  - `age_group`
  - `purchase_frequency_days`
- Loaded cleaned data into MySQL for analysis  

![](/jp_1.png)
---

## 🔽 SQL Business Analysis (MySQL)

Key analysis performed:
- Revenue by gender
- High-spending customers using discounts
- Top-rated products
- Shipping type vs purchase amount
- Subscriber vs non-subscriber analysis
- Discount-dependent products
- Customer segmentation (New, Returning, Loyal)
- Revenue by age group
 ![](/query_8.png)

---

## 📊 Power BI Dashboard
- Interactive filters for category, gender, and shipping type
- KPIs: Average Rating, Subscription Ratio, Revenue Distribution
- Designed for business users

---

## 💡 Key Insights
- Male customers generate significantly higher revenue
- Express shipping users spend more per order
- Subscription does not currently increase average spend
- Strong customer retention with a large loyal base

---

## 🚀 Business Recommendations
- Improve subscription benefits
- Target high-value customer segments
- Optimize discount strategy
- Promote top-performing products

---

## 🛠 Tools & Technologies
Python | SQL (MySQL) | Power BI | Pandas | EDA | Business Analytics

---

## 👤 Author
**Kirubakaran Balasubramanian**  
Aspiring Data Analyst (Fresher)  
🔗 LinkedIn: https://www.linkedin.com/in/kirubakaran-balasubramanian
