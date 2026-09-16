# 📊 Sales Performance Dashboard

An interactive **Sales Performance Dashboard** built using **Excel, SQL, and Microsoft Power BI** to analyze e-commerce sales performance, customer orders, products, payments, freight costs, and product-level performance.

The project transforms raw sales data into an interactive business intelligence dashboard that helps users understand **revenue trends, order performance, product contribution, payment behavior, shipping costs, and sales patterns**.

---

## 🚀 Project Overview

The objective of this project is to create a practical sales analytics solution that answers key business questions such as:

- How is sales revenue changing over time?
- Which products and categories contribute the most revenue?
- How many orders are being generated?
- What is the Average Order Value (AOV)?
- Which payment types are commonly used?
- How much freight cost is generated each year?
- Which days and hours show higher sales activity?
- How are products distributed across price ranges and review scores?

---

## 🛠️ Tools & Technologies

- **Excel** – Data preparation, cleaning, and initial analysis
- **SQL / MySQL** – Data handling and analytical preparation
- **Power BI** – Interactive dashboard development and visualization
- **DAX** – Measures and calculated metrics
- **Power Query** – Data transformation and preparation

---

## 📂 Dataset

The project uses an e-commerce sales dataset containing information from multiple related tables/files, including:

| Dataset | Description |
|---|---|
| `orders` | Order details, status, purchase and delivery dates |
| `order_items` | Product, seller, price, and freight information for each order item |
| `payments` | Payment type, installments, and payment value |
| `products` | Product category and product attributes |
| `geolocation` | Location information associated with customers/sellers |
| `reviews` | Customer review scores and review-related information |

---

## 🔄 Project Workflow

```text
Raw E-commerce Data
        ↓
Excel Data Preparation
        ↓
SQL / Data Handling
        ↓
Power Query Transformation
        ↓
Data Model
        ↓
DAX Measures
        ↓
Power BI Visualizations
        ↓
Interactive Sales Dashboard
```

---

# 📈 Dashboard Pages

## 1. Sales Performance Dashboard

The overview page provides a high-level view of overall sales performance.

### Key KPIs

- **Total Sales:** 13.59M
- **Total Orders:** 99K
- **Total Products:** 33K
- **Total Freight:** 2.25M

### Visualizations

- Monthly Sales Trend
- Top 10 Products
- Sales by Payment Type
- Order Status Distribution
- Freight Cost by Year
- Product Category Filter

### Key Analysis Areas

The page allows users to explore overall revenue trends, payment behavior, order status, product performance, and yearly freight costs.

![Sales Performance Dashboard](screenshots/dashboard-overview.png)

---

## 2. Sales Analysis

The Sales Analysis page provides a more detailed view of sales behavior.

### KPIs

- Total Sales
- Total Orders
- Average Order Value
- Total Freight

### Visualizations

- Sales by Sub Category
- Sales by Year
- Total Sales vs Sales Target
- Sales by Hour
- Sales by Day of Week

### Business Use

This page helps analyze:

- Yearly sales performance
- Product/sub-category contribution
- Average order value
- Customer purchase timing
- Daily sales patterns
- Sales target performance

![Sales Analysis](screenshots/sales-analysis.png)

---

## 3. Product Analysis

The Product Analysis page focuses on product-level performance.

### KPIs

- Total Products
- Total Orders
- Total Freight
- Average Order Value

### Visualizations

- Top 5 Sales Products
- Category Revenue Contribution
- Sales by Price Range
- Product Review Score
- Product Price vs Orders

### Business Use

This page helps identify:

- High-revenue products
- Major revenue-contributing categories
- Product price distribution
- Review-score distribution
- Relationship between product price and order volume

![Product Analysis](screenshots/product-analysis.png)

---

# 📊 Key Metrics

### Total Sales

Revenue generated from product sales and associated freight value based on the project's sales calculation.

### Average Order Value (AOV)

```text
AOV = Total Revenue ÷ Total Orders
```

The dashboard displays an AOV of approximately **137.74** based on the current dashboard data.

### Total Freight

Total freight/shipping value associated with the orders in the dataset.

---

# 🎯 Business Questions Answered

1. What is the overall sales revenue?
2. How are sales changing month by month?
3. Which products generate the highest sales?
4. Which product categories contribute significantly to revenue?
5. What is the average order value?
6. Which payment types are used by customers?
7. What is the distribution of order statuses?
8. How does freight cost change by year?
9. Which hours and days have higher sales activity?
10. How are products distributed across different price ranges?
11. How are product review scores distributed?
12. What is the relationship between product price and number of orders?

---

# 💡 Dashboard Features

- Interactive product-category filtering
- KPI cards
- Monthly trend analysis
- Product ranking
- Payment analysis
- Order-status analysis
- Freight-cost analysis
- Sales target comparison
- Time-of-day analysis
- Day-of-week analysis
- Product price analysis
- Review-score analysis
- Category revenue contribution

---

# 📌 Project Highlights

- Built a multi-page interactive Power BI dashboard.
- Created KPI-driven sales performance views.
- Analyzed product and category revenue contribution.
- Added time-based sales analysis by month, year, hour, and day.
- Included payment, order-status, freight, price, and review analysis.
- Used DAX measures for business metrics such as AOV.
- Designed the dashboard with navigation between Overview, Sales Analysis, and Product Analysis pages.

---

# 📁 Suggested Repository Structure

```text
Sales-Performance-Dashboard/
│
├── README.md
│
├── Dashboard/
│   └── Sales_Performance_Dashboard.pbix
│
├── Data/
│   ├── orders.csv
│   ├── order_items.csv
│   ├── payments.csv
│   ├── products.csv
│   ├── geolocation.csv
│   └── reviews.csv
│
├── Screenshots/
│   ├── dashboard-overview.png
│   ├── sales-analysis.png
│   └── product-analysis.png
│
└── Documentation/
    └── project-notes.md
```

> **Note:** Replace the example dataset and `.pbix` filenames with the exact files you upload to GitHub.

---

# 👨‍💻 Project Team

- **Jefrin Raj**
- **Saravanakumar**
- **Subha**
- **Priya**

---

# 📜 Project Type

**Milestone / Portfolio Project – Sales Analytics & Business Intelligence**

---

## ⭐ Conclusion

The Sales Performance Dashboard converts e-commerce data into an interactive analytical solution. It provides a centralized view of **sales, orders, products, payments, freight, customer purchase timing, and product performance**, helping users explore business performance through interactive Power BI visuals.

---

## 🔖 Skills Demonstrated

`Excel` `SQL` `Power BI` `DAX` `Power Query` `Data Cleaning` `Data Analysis` `Data Visualization` `Business Intelligence` `Dashboard Development` `KPI Analysis` `Sales Analytics`
