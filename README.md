#  E-Commerce Sales Analysis Dashboard

**Project Type:** End-to-End Business Analytics  
**Tech Stack:** SQL · Python · Power BI  
**Duration:** 3 Weeks  

---

##  Project Objective

This project was executed as a Business Analytics initiative for a mid-sized e-commerce company seeking to improve its sales performance and customer retention strategy through data-driven insights.
```
-The primary objectives included:
-Analyzing customer behavior and purchasing patterns across time, geography, and product categories to uncover key revenue drivers.
-Applying RFM (Recency, Frequency, Monetary) segmentation to classify customers into actionable groups such as loyal champions, one-time buyers, and at-risk users.
-Creating an interactive Power BI dashboard to visualize sales trends, payment preferences, product performance, and customer value distribution for business stakeholders.
-Providing strategic business recommendations to increase repeat purchases, implement loyalty and subscription models, and improve campaign targeting.
-This real-world Business Analytics project helped the company translate raw transactional data into actionable growth strategies
```
---

##  Tools & Technologies Used

| Tool      | Purpose                              |
|-----------|--------------------------------------|
| **SQL**   | Data cleaning, joins, transformation |
| **Python**| EDA, RFM analysis, visualizations    |
| **Power BI** | Interactive dashboard building     |
| **Pandas, Matplotlib, Seaborn** | Data analysis and visualization in Python |

---

##  Workflow Overview

### 1. **Data Collection & Understanding**
- Realistic e-commerce dataset with ~99K customers and 135K order items
- Data covers product orders, payments, reviews, and customer info

### 2. **SQL-Based Data Cleaning**
- Cleaned and joined datasets:
  - `customers`, `orders`, `order_items`, `payments`, `products`, etc.
- Filtered relevant time frame: **May 2016 – Oct 2018**

### 3. **Python EDA & RFM Segmentation**
- Data Cleaning -> merging -> RFM Segmentation -> Rating
- **Recency** = Days since last order  
- **Frequency** = Number of orders per customer  
- **Monetary** = Total payment value

## RFM Table:
| CustomerID                              | Recency | Frequency | Monetary | R | F | M | RFM_Score |
|----------------------------------------|---------|-----------|----------|---|---|---|-----------|
| 00012a2ce6f8dcda20d059ce98491703       | 287     | 1         | 114.74   | 2 | 1 | 3 | 6         |
| 000161a058600d5901f007fab4c27140       | 409     | 1         | 67.41    | 1 | 1 | 2 | 4         |
| 0001fd6190edaaf884bcaf3d49edf079       | 547     | 1         | 195.42   | 1 | 1 | 4 | 6         |
| 0002414f95344307404f0ace7a26f1d5       | 378     | 1         | 179.35   | 1 | 1 | 4 | 6         |
| 000379cdec625522490c315e70c7a9fb       | 149     | 1         | 107.01   | 3 | 1 | 3 | 7         |


---

##  Power BI Dashboard Insights

**Dashboard Includes:**
- Monthly Orders & Revenue Trend
- Revenue by Product Category & State
- Payment Type Distribution
- RFM-Based Customer Segmentation
- Year-over-Year Growth

![Power BI Dashboard](./Power-Bi%20Dashboard.png)

---

##  Key Analytical Insights

- **Customer Spend**: Most customers spend ₹50–₹300, very few spend ₹1000+
- **Order Frequency**: ~85–90% customers are one-time buyers
- **Payment Method**: Credit Cards dominate (75%+)
- **Top Revenue States**: SP, RJ, MG
- **Category Leaders**: Health, Watches, Computing products

---

##  Final Business Recommendations

1. **Launch Loyalty Program**  
   To increase frequency among one-time buyers

2. **Re-engagement Campaigns**  
   Target low-frequency, high-recency customers

3. **Upsell to High RFM Segments**  
   Promote high-value bundles to top 10% customers

4. **Subscription-Based Models**  
   For customers with high monetary but low frequency

5. **Combo & Bundling Offers**  
   Increase AOV (Average Order Value) and repeat purchases

---

##  Project Structure
```
/Financial_Analytics
│
├── SQL/
│   └── data_cleaning_queries.sql
│
├── Python/
│   └── RFM_analysis.ipynb
│
├── PowerBI/
│   └── Dashboard.pbix
│   └── Power-Bi Dashboard.png
│
└── README.md
```


