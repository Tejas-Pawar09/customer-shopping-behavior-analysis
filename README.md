# Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes 3,900 customer purchase transactions to identify revenue-driving customer segments, evaluate the impact of subscriptions on customer spending, and assess product and discount strategies to support data-driven business decisions.

The analysis follows an end-to-end data analytics workflow using **Python, SQL, and Power BI**.

---

## 📊 Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  

**Key Features:**
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Shopping Behavior:** Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type  

**Data Quality:**
- 37 missing values in the *Review Rating* column (<1% of data), handled during preprocessing to avoid bias in product rating analysis.

---

## 🧹 Exploratory Data Analysis (Python)
Python was used for data preparation, validation, and feature engineering before SQL-based analysis.

- Loaded and inspected data using pandas
- Performed structural and statistical exploration
- Handled missing review ratings using median imputation by product category
- Standardized column names to snake_case
- Engineered features such as:
  - `age_group` for demographic analysis
  - purchase frequency–related features for behavioral analysis
- Removed redundant columns after consistency checks
- Loaded cleaned data into MySQL for SQL-based business analysis


---

## 🗄️ Data Analysis (SQL)
Structured SQL queries were used to answer key business questions, including:

1. Revenue contribution by gender  
2. High-spending customers using discounts  
3. Top-rated products based on average review ratings  
4. Purchase behavior across shipping types  
5. Spending comparison between subscribers and non-subscribers  
6. Products most dependent on discounts  
7. Customer segmentation (New, Returning, Loyal)  
8. Top products within each category  
9. Subscription behavior of repeat buyers  
10. Revenue contribution by age group  

Advanced SQL concepts such as **CTEs, window functions, subqueries, and aggregations** were applied using MySQL.

---

## 📈 Power BI Dashboard
An interactive Power BI dashboard was built to visualize key insights and enable business-focused decision-making.

**Dashboard Highlights:**
- KPIs: Total Customers, Average Purchase Amount, Average Review Rating
- Revenue and order trends by category and age group
- Subscription vs non-subscription comparison
- Customer segmentation analysis
- Interactive slicers for gender, category, subscription status, and shipping type

---

## 💡 Key Business Insights
- A small segment of customers contributes a disproportionately high share of revenue
- Subscribers demonstrate higher average spending compared to non-subscribers
- Certain products rely heavily on discounts, impacting profitability
- Specific age groups drive the majority of revenue and engagement

---

## 📌 Business Recommendations
- Promote subscriptions among high-spending non-subscribers
- Strengthen loyalty programs for repeat customers
- Optimize discount strategies to balance sales growth and margins
- Focus marketing efforts on top-performing age groups and product categories

---

## 🛠️ Tools & Technologies
- **Python:** pandas, numpy  
- **SQL:** MYSQL  
- **Visualization:** Power BI  

---

## 📁 Project Structure
