# 🛒 E-Commerce Sales Analysis — Power BI Dashboard

An interactive **Power BI E-Commerce Sales Analytics Dashboard** built to analyze sales performance, profitability, customer behavior, product performance, payment methods, and regional trends.

The project transforms a 1,000-order e-commerce dataset into an executive-friendly dashboard designed to support **data-driven business decisions**.

---

## 📊 Dashboard Preview

![E-Commerce Sales Analysis Dashboard](./dashboard.png)

> **Dashboard focus:** Sales | Profit | Products | Customers | Regional Performance | Business Insights

---

## 🎯 Business Objective

The objective of this project is to understand **what is driving revenue and profit**, identify high-performing products and categories, evaluate customer segments and payment behavior, and highlight areas where the business can improve its commercial performance.

The dashboard is designed from a **business analyst / data analyst perspective**, rather than simply presenting charts.

### Key business questions answered

- How much revenue and profit did the business generate?
- What is the overall profit margin?
- Which products and categories contribute the most to revenue?
- Which products have stronger profitability?
- Which months generate the highest sales?
- Which customer segments contribute the most revenue?
- Which payment methods are most commonly used?
- How do delivered, returned, and cancelled orders affect the business?
- Which cities are generating the highest sales?
- Where should management focus to improve profitability and reduce revenue leakage?

---

## 📌 Executive KPI Snapshot

| KPI | Result |
|---|---:|
| **Total Sales** | ₹23.59M |
| **Total Profit** | ₹5.14M |
| **Profit Margin** | **21.78%** |
| **Total Orders** | 1,000 |
| **Total Customers** | 296 |
| **Total Quantity Sold** | 3,036 |
| **Average Order Value** | ₹23,590 |
| **Average Profit / Order** | ₹5,137 |

**Analysis period:** January 2025 – December 2025

---

# 🔎 Key Business Insights

## 1. Electronics is the dominant revenue category

**Electronics generated ₹16.52M in sales**, contributing roughly **70% of total revenue**.

The next largest categories were:

- Furniture — ₹2.80M
- Home Appliances — ₹2.41M
- Fashion — ₹1.05M

### Business interpretation
The business is highly dependent on Electronics. This creates a strong revenue engine, but also introduces **category concentration risk**.

### Recommendation
Continue investing in high-performing Electronics products while developing Furniture and Home Appliances to diversify the revenue mix.

---

## 2. Laptop is the strongest individual product

**Laptop generated ₹10.00M in sales and ₹2.11M in profit**, making it the clear leading product by revenue and profit.

Other strong contributors include:

- Smartphone — ₹5.03M sales / ₹1.12M profit
- Office Chair — ₹1.52M sales / ₹0.33M profit
- Desk — ₹1.28M sales / ₹0.31M profit

### Business interpretation
Laptop and Smartphone together generate a substantial share of total revenue, making them critical products for inventory planning, promotions, and cross-selling.

---

## 3. October was the strongest sales month

The highest monthly sales were recorded in:

| Month | Sales |
|---|---:|
| **October** | **₹2.99M** |
| November | ₹2.68M |
| June | ₹2.48M |
| March | ₹2.09M |

April was the weakest month at approximately **₹1.01M**.

### Business interpretation
The large difference between peak and low months suggests meaningful **seasonality or campaign-driven demand**.

### Recommendation
Use stronger inventory availability and promotional planning before high-demand periods, while testing targeted campaigns during weaker months.

---

## 4. Delivered orders drive the majority of realized business activity

The dataset contains:

- **592 Delivered orders**
- **200 Returned orders**
- **208 Cancelled orders**

That means only **59.2% of orders were delivered**.

### Business interpretation
The relatively high proportion of returned and cancelled orders is an important operational signal.

Even though the dashboard shows strong overall revenue and profit, order-status performance should be monitored because cancellations and returns can create:

- Revenue leakage
- Additional logistics costs
- Inventory inefficiency
- Lower customer satisfaction
- Working-capital pressure

### Recommendation
Investigate cancellation and return patterns by **product, city, customer segment, and payment method** to identify the underlying drivers.

> **Note:** Order-status sales values in the source dataset should be interpreted carefully because the dataset records sales/profit values for each order status. The dashboard therefore focuses on status distribution as an operational KPI rather than assuming every recorded amount represents realized revenue.

---

## 5. Small Business customers are the largest revenue segment

Revenue contribution by customer segment:

| Customer Segment | Sales | Orders |
|---|---:|---:|
| **Small Business** | **₹9.15M** | 358 |
| Corporate | ₹7.73M | 346 |
| Consumer | ₹6.71M | 296 |

### Business interpretation
Small Business customers represent the largest customer segment by sales and order volume.

### Recommendation
Create dedicated B2B-style offers such as:

- Bulk purchase discounts
- Business bundles
- Repeat-order incentives
- Account-based promotions

---

## 6. UPI and Credit Card are the leading payment methods

| Payment Method | Sales |
|---|---:|
| **UPI** | **₹5.49M** |
| Credit Card | ₹5.41M |
| Debit Card | ₹4.58M |
| Net Banking | ₹4.29M |
| Cash on Delivery | ₹3.82M |

### Business interpretation
Digital payment methods dominate the dataset, with UPI and Credit Card together representing the largest payment channels.

### Recommendation
Prioritize a smooth UPI/card checkout experience and use payment-specific promotions carefully to increase conversion without unnecessarily reducing margins.

---

## 7. Profitability differs across product categories

Category-level profit margins show that:

- **Furniture:** ~22.94%
- **Fashion:** ~22.36%
- **Home Appliances:** ~22.11%
- **Electronics:** ~21.56%
- **Accessories:** ~21.44%
- **Bags:** ~18.68%

### Business interpretation
Electronics produces the most absolute profit, but Furniture has a slightly stronger margin.

This distinction is important:

> **Highest revenue does not always mean highest profitability.**

A good commercial strategy should evaluate both **revenue contribution and margin contribution**.

---

## 8. Desk and Air Fryer show strong product-level margins

Among the products, some of the stronger profit margins are:

- Desk — ~24.13%
- Air Fryer — ~23.73%
- Shoes — ~23.04%
- Smartwatch — ~22.52%

### Recommendation
These products can be evaluated for:

- Cross-selling opportunities
- Bundle offers
- Higher visibility
- Targeted promotions
- Inventory prioritization

---

## 9. Regional performance shows clear differences

Top cities by sales include:

| City | Sales |
|---|---:|
| **Surat** | **₹1.84M** |
| Delhi | ₹1.72M |
| Hyderabad | ₹1.60M |
| Jaipur | ₹1.36M |
| Mysuru | ₹1.30M |

### Business interpretation
Surat, Delhi, and Hyderabad are important regional revenue markets.

However, sales alone should not determine market priority. Regional decisions should also consider **profitability, order volume, and customer behavior**.

---

# 💡 Analyst Recommendations

Based on the dashboard analysis, the following actions would have the highest potential business value:

### 1. Reduce dependency on Electronics
Electronics contributes the majority of sales. Expand high-margin categories such as Furniture and Home Appliances to create a more balanced revenue mix.

### 2. Investigate cancellation and return drivers
With 408 of 1,000 orders classified as cancelled or returned, management should perform a deeper root-cause analysis.

Recommended dimensions:

`Product → Category → City → Customer Segment → Payment Method → Order Status`

### 3. Protect high-value products
Laptop and Smartphone are major revenue/profit contributors. Inventory availability and pricing for these products should be closely monitored.

### 4. Improve weak-period performance
April recorded the lowest monthly sales. Analyze campaigns, product availability, customer demand, and pricing during low-performing periods.

### 5. Develop Small Business accounts
Small Business customers are the largest revenue segment. Dedicated B2B offers and repeat-purchase programs could increase customer lifetime value.

### 6. Optimize for profitable growth
Do not optimize only for sales volume. Track:

**Sales + Profit + Margin + Order Status + Customer Segment**

together when evaluating business performance.

---

# 📈 Dashboard Features

The Power BI dashboard includes:

- **Executive KPI cards**
- Monthly Sales Trend
- Sales by Category
- Sales by Payment Method
- Profit by Product
- Product-level performance table
- City filter
- Order Status filter
- Category filter
- Customer Segment filter
- Month-wise navigation
- Interactive cross-filtering

### Dashboard Navigation

The report is structured around:

**Sales | Profit | Products | Customers | Regional Performance | Business Insights**

This allows users to move from high-level KPIs to detailed business analysis.

---

# 🧰 Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development and data visualization |
| **Power Query** | Data transformation and preparation |
| **DAX** | KPI and analytical measure development |
| **CSV** | Source dataset |
| **Data Modeling** | Organizing analytical relationships and reporting logic |

---

# 🗂️ Dataset Overview

The project uses an e-commerce transaction dataset containing **1,000 orders** across the 2025 calendar year.

### Main fields

| Field | Description |
|---|---|
| `Order_ID` | Unique order identifier |
| `Order_Date` | Order transaction date |
| `Customer_ID` | Customer identifier |
| `Product` | Purchased product |
| `Category` | Product category |
| `Quantity` | Units purchased |
| `Unit_Price` | Price per unit |
| `Discount` | Applied discount |
| `Sales` | Sales value |
| `Cost` | Product cost |
| `Profit` | Profit generated |
| `State` | Customer state |
| `City` | Customer city |
| `Payment_Method` | Payment channel |
| `Order_Status` | Delivered / Returned / Cancelled |
| `Customer_Segment` | Consumer / Corporate / Small Business |

---

# 🧮 Core Analytical Metrics

The dashboard focuses on standard business KPIs such as:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Total Quantity
- Profit Margin %
- Average Order Value
- Sales by Category
- Sales by Product
- Sales by Customer Segment
- Sales by Payment Method
- Regional Sales
- Monthly Sales Trend

---

# 🏗️ Analytical Approach

The project follows a practical analytics workflow:

**Raw Data → Data Cleaning → Data Transformation → Data Modeling → DAX Measures → Visualization → Business Insights → Recommendations**

The goal is not only to visualize historical data but to convert the data into **actionable business insights**.

---

# 📁 Repository Structure

```text
Ecommerce-Sales-Analysis/
│
├── README.md
├── Ecommerce_Sales_Dataset_1000_Rows.csv
├── dashboard.png
└── E-Commerce Sales Analysis.pbix
```

> The `.pbix` file is the main Power BI report.  
> The CSV contains the source transaction data.  
> The PNG file provides a preview of the dashboard.

---

# 🚀 How to Use

1. Download or clone this repository.
2. Open the `.pbix` file in **Microsoft Power BI Desktop**.
3. If required, update the CSV source path.
4. Refresh the dataset.
5. Use the slicers and visual interactions to explore the analysis.
6. Review the KPI cards and business insights for decision-making.

---

# 📌 Key Takeaway

The analysis shows a business with **₹23.59M in recorded sales, ₹5.14M in profit, and a 21.78% profit margin**.

The strongest commercial opportunities are concentrated around:

**Electronics → Laptop & Smartphone → Small Business customers → Digital payments → High-performing cities**

At the same time, the **high cancellation/return share** represents an important operational area for further investigation.

From a data analytics perspective, the key lesson is:

> **Revenue tells you where the business is winning; profitability and operational metrics tell you whether that growth is sustainable.**

---

## 👤 Project Author

**Nitesh Yadav**

Data Analytics Portfolio Project

**Focus Areas:**  
Power BI • SQL • Excel • Data Analysis • Business Intelligence

---

## ⭐ If you found this project useful

Feel free to ⭐ the repository and explore the Power BI dashboard.
