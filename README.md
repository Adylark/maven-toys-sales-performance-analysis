# Maven Toys Sales Performance Analysis
<img width="1435" height="805" alt="Sales Performance" src="https://github.com/user-attachments/assets/00ae42d3-b937-4e84-98ca-b2f8d9dc1ab3" />
<img width="1439" height="805" alt="Store Overview" src="https://github.com/user-attachments/assets/70f341cb-2b13-4935-95aa-a6efcf872ea7" />



## Project Overview
This project analyzes the sales performance, profitability, and inventory efficiency of a retail company (Maven Toys) using PostgreSQL -> Python -> Power BI.

The goal is to transform raw transactional and inventory data into actionable business insights that support decision-making.

---

## Business Problem
The company faces challenges in:
- Understanding revenue and profit trends
- Identifying top-performing products and categories
- Managing inventory efficiently across warehouses
- Detecting slow-moving or overstocked products
- Evaluating store performance by location

---

## Analytical Questions
1. How does revenue and profit trend over time?
2. Which product categories contribute the most revenue?
3. What is the current inventory health across warehouses?
4. Which products are at risk of overstock (dead stock)?
5. How efficient is inventory compared to sales velocity?
6. Which store locations drive the highest revenue?

---

## Tools & Technologies
- PostgreSQL
- Python
- Power BI
- CSV Dataset

---

##  Data Processing Steps
1. Data Injection (because raw data was clean)
2. Data Cleaning (handling missing values, formatting)
3. Data Transformation using Power Query
4. Building DAX Measures (Revenue, Profit, Inventory Metrics)
5. Creating Dashboard & Visualizations

---

## Key Insights

### 1. Revenue & Profit Trend
- Revenue shows consistent growth with seasonal fluctuations
- Profit margins vary, indicating cost inefficiencies in certain periods

### 2. Product Contribution
- A small number of products contribute the majority of revenue (Pareto effect)
- Some categories dominate overall sales

### 3. Inventory Health
- Several warehouses have high stock levels with low sales movement
- Indicates imbalance in stock distribution

### 4. Dead Stock Risk
- Certain products have high inventory but low sales velocity
- These products tie up capital and reduce efficiency

### 5. Inventory Efficiency
- Some products sell quickly but are understocked
- Others are overstocked with slow turnover

### 6. Store Performance
- Urban/high-traffic locations generate the highest revenue
- Some locations underperform despite having similar inventory

---

## Recommendations

### Inventory Optimization
- Reallocate stock from low-performing warehouses to high-demand locations
- Implement minimum & maximum stock thresholds

### Product Strategy
- Focus on high-performing products
- Discount or bundle slow-moving products to reduce dead stock

### Demand-Based Stocking
- Align inventory with sales velocity
- Use historical sales data for forecasting

### Store Performance Improvement
- Analyze underperforming stores
- Optimize product mix based on location demand

---

## Dashboard Preview
<img width="1440" height="808" alt="Inventory Health" src="https://github.com/user-attachments/assets/14f2477d-e3f6-4237-ad4e-87b07105583a" />



---

## Project Files
- `dashboard/` → Power BI file
- `presentation/` → Final presentation slides
- `data/` → Dataset (raw & cleaned)
- `images/` → Dashboard screenshots

---

## Author
**Fadhil** – Aspiring Data Analyst  
Focus: Power BI, SQL, Data Analysis
