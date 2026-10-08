# vertex-business-sales-analysis
Interactive 3-page Power BI dashboard analysing sales, profitability and customer behaviour (Jan 2024 - May 2026). 

## Dashboard Preview

### Overview
[Overview](https://github.com/taryilabem/vertex-business-sales-analysis/blob/main/screenshots/Screenshot%202026-10-07%201.png)

### Profitability Analysis
[Profitability Analysis](https://github.com/taryilabem/vertex-business-sales-analysis/blob/main/screenshots/Screenshot%202026-10-07%203.png)

### Customer and Product Analysis
[Customer and Product Analysis](https://github.com/taryilabem/vertex-business-sales-analysis/blob/main/screenshots/Screenshot%202026-10-07%203.png)

---

## 1. Objective

To give business stakeholders a single, interactive view of how the business is performing, so they can:

- Track overall sales, profit and order performance
- Identify the products, categories, channels and states that drive revenue and profit
- Understand who the customers are and how they buy and pay
- Spot weak areas (low-margin products, returns, discounting) and make data-driven decisions

---
## 2. Description

The report has three pages, connected by a navigation pane and shared slicers.

**Page 1: Overview (Sales Dashboard)**
- KPI cards: Total Sales, Total Profit, Total Orders, Average Order Value, Profit Margin, Return Rate
- Visuals: Monthly Sales Trend (2024 vs 2025 vs 2026), Sales by State (map), Sales by Category, Top 5 Products by Sales, Profit by Customer Segment, Sales by Channel, Discount vs Profit, Return Analysis, Sales vs Profit by State
- Filters: Year, State, Product Category, Sales Channel, Customer Segment, Order Status

**Page 2: Profitability Analysis**
- KPI cards: Total Sales, Total Profit, Profit Margin
- Visuals: Sales vs Profit by State, Discount vs Profit, Profit by Product, Profit Margin by Category, Profit by Channel, Profit by Customer Segment, Top 5 Most Profitable Products, Bottom 5 Products by Profit Margin

**Page 3: Customer & Product Analysis**
- KPI cards: Total Orders, Average Order Value
- - Visuals: Customer Segment split, Sales by Age Group, Sales by Product, Quantity by Product, Average Order Value by Segment, Payment Method, Sales by State, Sales by Product Category

**Tools:** Power BI (data modelling, DAX measures, visuals, slicers, page navigation)

---
## 3. KPI Questions Answered

**Overall performance**
1. What are the total sales, profit and profit margin for the period?
2. How many orders were placed and what is the average order value?
3. How are monthly sales trending across 2024, 2025 and 2026?
4. What is the return rate?

**Products and categories**
5. Which products generate the most sales and the most profit?
6. Which product category contributes the most revenue?
7. Which products sell in the highest quantities?
8. Which products have the lowest profit margins?

**Channels and geography**
9. Which sales channel (Online, Retail Store, Wholesale, Marketplace) performs best?
10. Which states generate the most sales and profit?

**Customers**
11. Which customer segment brings in the most sales and profit?
12. Which age group spends the most?
13. Which segment has the highest average order value?
14. Which payment methods do customers prefer?

**Profitability and risk**
15. What is the relationship between discounts and profit?
16. How many orders were completed vs returned?

---

## 4. Key Insights

**Overview**
- The business recorded **$3.27M in sales** and **$1.17M in profit**, a **36% profit margin**, from about **1,000 orders**.
- Average order value is high at about **$3.27K**, which points to a high-ticket product mix.
- Return rate is very low: **19 of 1,000 orders (1.9%)** were returned and 98.1% completed.
- Monthly sales sit mostly between $0.1M and $0.2M, with no strong seasonal pattern. 2025 and 2024 follow similar paths, while 2026 shows a sharp rise in April.

**Products and categories**
- **Electronics dominates revenue**, at roughly 2.3M of the 3.27M total. Furniture is second and Accessories is the smallest.
- **Laptops are the top product** by both sales (about $1.01M) and profit (about $0.35M). The top 5 by sales are Laptop, Smartphone ($0.48M), Tablet ($0.39M), Desk ($0.28M) and Monitor ($0.23M).
- **Volume and value differ.** The best sellers by quantity (Backpack, Printer, Tablet, Keyboard, Bookshelf) are mostly lower-priced items, so high volume does not mean high revenue.

**Channels and geography**
- **Online is the largest channel** for both sales and profit, followed by Retail Store, Wholesale and Marketplace.
- Sales and profit by state show a strong, near-linear relationship, so states with higher sales reliably deliver higher profit. Sales are spread across many states without extreme concentration.

**Customers**
- **Consumers are the biggest segment** (about 45% of customers) and the most profitable (about $0.5M), followed by Corporate, Small Business and Enterprise.
- Average order value is fairly even across segments, from **$3.4K (Consumer)** down to **$2.9K (Enterprise)**.
- **The 35-44 age group spends the most**, followed by 25-34 and 45-54. The 18-24 group spends the least.
- **Credit card is the most-used payment method**, followed by debit card, with bank transfer, PayPal and digital wallet behind.

**Discounts**
- Higher discount values appear alongside higher profit. This is most likely because bigger, high-value orders (especially Electronics) attract larger discounts, so it should not be read as discounts causing profit.

---

## 5. Conclusions and Recommendations

1. **Protect and grow Electronics**, especially Laptops, Smartphones and Tablets, since they carry both revenue and profit.
2. **Invest in the Online channel**, the strongest performer, and review how to lift Marketplace and Wholesale.
3. **Prioritise Consumer and Corporate customers** with targeted campaigns, and focus on the 25-54 age range.
4. **Look at the Enterprise segment.** It has the lowest sales, profit and order value, so there may be untapped potential or a mismatch in the offer.
5. **Review low-margin products** (for example Headphones, Office Chair, Monitor, Mouse) for pricing or cost improvements.
6. **Test discounts carefully.** Run controlled comparisons before concluding that bigger discounts lift profit.
7. **Keep returns low.** At 1.9% the return rate is healthy, so continue current quality and fulfilment practices.
## 7. Repository Structure (suggested)

```
vertex-sales-dashboard/
├── README.md
├── dashboard/
│   └── Vertex_Sales_Dashboard.pbix
├── data/
│   └── sales_data.csv
└── screenshots/
    ├── 01_overview.jpeg
    ├── 02_profitability.jpeg
    └── 03_customer_product.jpeg
```

---

## 8. Author

**Taryila Emmanuel Bem**
Data Analytics professional with skills in Excel, SQL, Power BI, Machine Learning and R, passionate about transforming data into actionable insights.

- Visuals: Customer Segment split, Sales by Age Group, Sales by Product, Quantity by Product, Average Order Value by Segment, Payment Method, Sales by State, Sales by Product Category
