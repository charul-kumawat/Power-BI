# Dashboard Portfolio | Charul Kumawat

Hi, I am Charul, a market research analyst with experience in data and research-driven decision making to drive organization growth. This portfolio highlights my skills as a business analyst.

## 📊 AdventureWorks Sales Performance Dashboard

A multi-page Power BI dashboard designed to analyze **sales performance, customer behavior, product trends, and regional distribution** to support data-driven business decisions.

---

## 📌 Table of Contents

- [Business Objective](#business-objective)
- [Dashboard Overview](#dashboard-overview)
- [Customer Analysis](#customer-analysis)
- [Product Performance Analysis](#product-performance-analysis)
- [Regional Analysis](#regional-analysis)
- [Trend Analysis](#trend-analysis)
- [Data Model](#data-model)
- [DAX & Analytical Techniques](#dax--analytical-techniques)
- [Key Business Impact](#key-business-impact)
- [Contact](#contact)

---

## 🎯 Business Objective

To identify key drivers of:

* Revenue and profit growth
* Customer purchasing behavior
* Product performance and return trends
* Regional sales distribution

The goal is to enable stakeholders to make **strategic decisions around sales optimization, customer targeting, and product strategy**.

---

## Dashboard Overview

### EXECUTIVE SUMMARY

| Metric | Value |
|--------|------|
| Revenue | $24.9M |
| Profit | $10.5M |
| Orders | 25.2K |
| Return Rate | 2.2% |

<img width="1333" height="754" alt="First Page" src="https://github.com/user-attachments/assets/c421ebd1-e847-47da-9c32-3984a9f4679b" />

The dashboard shows a strong scale of business with $24.9M revenue, $10.5M profit, 25.2K orders, and a relatively low 2.2% return rate. This indicates a healthy business with good profitability and controlled return leakage.

---

### CUSTOMER ANALYSIS

* Total Customers: **17.4K**
* Revenue per Customer: **$1.4K**

Key capabilities:

* Identify **top 100 customers by revenue**
* Analyze **orders by income level and occupation**
* Track **customer growth trends over time**

<img width="1338" height="755" alt="Customer Detail Page" src="https://github.com/user-attachments/assets/bafbad6b-b25e-495d-81ce-45829ec56535" />

👉 **Insight:** The business serves about 17.4K unique customers, generating around $1.4K revenue per customer on average. The top customer alone generated $12.4K revenue from just 6 orders. Revenue is not evenly distributed; a small set of high-value customers contributes disproportionately, making retention and account management strategically important.

---

### PRODUCT PERFORMANCE ANALYSIS

* Tracks **top-performing products by revenue and orders**
* Monitors **return percentage per product**
* Compares **monthly targets vs actual performance**

Key feature:

* Dynamic **price adjustment simulation** to evaluate impact on profit

<img width="1333" height="750" alt="Product Detail Page" src="https://github.com/user-attachments/assets/b46f26b9-853f-4533-a9b9-283d2d9e2868" />


👉 **Insight:** The Water Bottle - 30 oz. is the top product in the detail view, with 3,983 orders and $39,755 revenue. Other products such as Sport-100 Helmet, Red and AWC Logo Cap also contribute significant revenue. A small number of products drive a large share of sales, so inventory planning and promotion strategy should prioritize these high-volume items.

---

### REGIONAL ANALYSIS

* Sales distribution across:

  * North America
  * Europe
  * Pacific

Interactive map enables:

* Geographic performance comparison
* Identification of high-performing regions

<img width="1333" height="752" alt="Map Page" src="https://github.com/user-attachments/assets/84184cc7-1f07-47f6-adbf-c1140f5b62c5" />

👉 **Insight:** The map shows strong sales presence in the United States, Canada, United Kingdom, France, Germany, and Australia, with the U.S. appearing as the dominant market. Sales are geographically concentrated, which helps identify priority regions for growth and localization.

---

### TREND ANALYSIS

* Monthly revenue, profit, and order tracking
* Rolling metrics using DAX
* Target vs actual comparisons

👉 **Insight:** The monthly trend charts show an upward trajectory in revenue and customers over time, with visible spikes in the later period.
The business appears to be growing steadily rather than stagnating, and the later spikes may indicate seasonal demand or successful campaigns.

---

## Data Model

* Star schema structure with:

  * Fact Table: **Sales Data**
  * Dimension Tables:

    * Customer Lookup
    * Product Lookup
    * Territory Lookup
    * Calendar Lookup

<img width="694" height="796" alt="Data Model" src="https://github.com/user-attachments/assets/bb8917d8-dd7b-43f0-b4cc-65396afdb62e" />

👉 The data model uses a star-schema structure with fact and dimension tables, and the measures page shows advanced DAX logic for rolling metrics, adjusted profit, target comparison, and customer/product segmentation.

---

## DAX & Analytical Techniques

Implemented advanced DAX measures such as:

* Rolling revenue and profit metrics
* Target vs actual comparisons
* High-ticket order identification
* Adjusted profit calculations

<img width="1768" height="801" alt="Measure Tables" src="https://github.com/user-attachments/assets/12b8ab33-5a10-46b9-83a6-091915d99187" />

Example:

```DAX
High Ticket Orders =
CALCULATE(
    [Total Orders],
    FILTER(
        'Product Lookup',
        'Product Lookup'[ProductPrice] > [Overall Average Price]
    )
)
```

## Key Business Impact

- The business generated $24.9M in revenue and $10.5M in profit across 25.2K orders, with a low 2.2% return rate, indicating strong overall performance.
- Revenue is concentrated among a relatively small number of high-value customers; the top customer alone contributed $12.4K from only 6 orders. Retention of these customers will be beneficial.
- Middle-income and professional customer groups drive the largest share of orders, making them the most commercially important segments.
- Product performance is skewed toward a few high-volume items, with the Water Bottle - 30 oz. leading at 3,983 orders and $39,755 revenue.
- Return rates vary by product, showing that some high-selling products may need quality or expectation management.
- Sales are concentrated across a few key international regions, with the United States appearing as the largest market.
- Monthly revenue and customer volume show an upward trend over time, suggesting business growth and improving demand.
- Target-versus-actual analysis and price adjustment scenarios add a decision-support layer to the dashboard.

---

## 📬 Contact

* LinkedIn: https://www.linkedin.com/in/charul-kumawat-03526b239/
* Email: [charulk97@gmail.com](mailto:charulk97@gmail.com)

