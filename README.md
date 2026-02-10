---

## Amazon Sales Dashboard – Power BI Project

### Project Overview

This project presents an **interactive Amazon Sales Dashboard** built using **Power BI**.
The dashboard provides insights into sales performance, product demand, customer behavior, and regional trends, enabling data-driven business decisions.

---

### Business Problem

The organization lacked a centralized, interactive reporting system to monitor sales across product categories, regions, and payment methods.
Static reports made it difficult to:

* Track sales trends over time
* Identify top-performing products
* Analyze discount impact
* Monitor customer satisfaction
* Compare regional performance

This Power BI dashboard solves these challenges by providing real-time, interactive insights.

---

### Objectives

* Monitor overall sales performance
* Identify top product categories and products
* Analyze the effect of discounts on revenue
* Evaluate customer ratings
* Compare sales across regions
* Understand payment method preferences

---

### Key KPIs

* **Total Sales:** 32.87M
* **Total Orders:** 50K
* **Total Quantity Sold:** 150K
* **Average Rating:** 3
* **Average Discount:** 13%

---

### Dashboard Features

#### 1. Sales Overview

* KPI cards for revenue, orders, quantity, rating, and discount
* Monthly sales trend analysis

#### 2. Product Performance

* Sales by product category
* Category-wise contribution (treemap)
* Top-performing categories

#### 3. Regional Analysis

* Interactive world map showing regional sales distribution

#### 4. Customer Insights

* Payment method distribution (donut chart)
* Average rating by category

#### 5. Interactive Filters

* Month
* Product Category
* Region
* Payment Method
* Rating

---

### Tools & Technologies

* **Power BI Desktop**
* **Power Query** for data transformation
* **DAX** for calculated measures
* **Data Visualization** best practices

---

### Data Source

Sample Amazon sales dataset used for learning and dashboard development purposes.

---

### Key DAX Measures

```DAX
Total Sales = SUM(Sales[Revenue])

Total Orders = DISTINCTCOUNT(Sales[Order ID])

Total Quantity = SUM(Sales[Quantity])

Average Rating = AVERAGE(Sales[Rating])

Average Discount = AVERAGE(Sales[Discount %])
```

---

### Dashboard Screenshots

---

<img width="1055" height="601" alt="IMG_0459" src="https://github.com/user-attachments/assets/89a20999-c5a2-49a9-b068-c9485143bee6" />
<img width="1053" height="597" alt="IMG_0458" src="https://github.com/user-attachments/assets/b358bb2f-459f-4b1e-9c85-9e85a4cee890" />
<img width="1060" height="597" alt="IMG_0457" src="https://github.com/user-attachments/assets/39f97533-a26f-42f7-b6f6-2ab74439b9c7" />

---

### How to Use

1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. Interact with filters and visuals to explore insights.

---

### Project Structure

```
Amazon-Sales-Dashboard/
│
├── Amazon_Sales_Dashboard.pbix
├── dataset/
│   └── amazon_sales_dataset.csv
├── screenshots/
│   ├── overview.png
│   ├── customer_insights.png
│   └── sales_trends.png
└── README.md
```

---

### Insights from the Dashboard

* Sales are consistent across months with slight seasonal variations.
* Electronics and Fashion contribute significantly to revenue.
* Payment methods are evenly distributed.
* Average customer rating remains stable across categories.

---
