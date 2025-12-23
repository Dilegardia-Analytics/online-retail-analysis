# online-retail-analysis

# 📊 Online Retail Sales Performance & Product Strategy Analysis

## Overview
This project presents a **full data quality audit, exploratory analysis, and business-driven strategy assessment** of transactional data from an online retail company.

The objective is not only to describe historical performance, but to **translate data insights into concrete commercial recommendations** related to product strategy, pricing actions, customer concentration risk, and geographic dependence.

The analysis is designed to **mirror the real-world workflow of an entry-level data analyst** working with business stakeholders and decision-makers.

---

## Business Questions Addressed
- When does the business generate most of its revenue?
- Is revenue growth driven by pricing or sales volume?
- Which products should be protected, promoted, discounted, or discontinued?
- How concentrated is revenue across customers and countries?
- Where do operational or strategic risks exist?

---

## Dataset
- **Source:** Online retail transactional data  
- **Period:** December 2010 – December 2011  
- **Initial size:** ~541,000 transactions  
- **Validated analysis base:** ~530,000 genuine sales transactions  

Each transaction includes:
- Invoice details  
- Product information  
- Quantities and prices  
- Customer identifiers  
- Timestamps  
- Country  

---

## Methodology
The project follows a **business-first analytical workflow**:

### 1. Data Quality Audit
- Identification of cancellations, returns, and zero-priced records  
- Separation of operational charges (postage, manual adjustments)  
- Validation of quantities, prices, and timestamps  

### 2. Revenue & Seasonality Analysis
- Monthly revenue trend analysis  
- Identification of seasonal demand patterns  

### 3. Revenue Drivers
- Decomposition of revenue into **volume vs price effects**  

### 4. Product Performance Analysis
- Top products by revenue and by demand  
- Separation of traffic drivers vs value drivers  

### 5. Customer & Geographic Concentration
- Revenue concentration across customers  
- Country-level dependency analysis  

### 6. Strategic Product Segmentation
Products are classified into four strategic categories:
- **Core Drivers**
- **Traffic Drivers**
- **Premium Opportunities**
- **Underperformers**

---

## Key Insights
- Revenue growth is **volume-driven**, not price-driven  
- A small subset of products forms the **core revenue backbone**  
- A large portion of the catalog **underperforms and adds operational complexity**  
- Revenue is **highly concentrated** among a limited number of customers  
- The business shows strong **geographic dependence on the UK market**

---

## Strategic Recommendations
- Protect and prioritize availability of **core revenue products**
- Use high-volume, low-price items for **bundling and traffic generation**
- Improve visibility and positioning of **premium products** instead of discounting them
- Consider **clearance or removal** of low-value, low-demand products
- Reduce dependency risk by **diversifying customers and geographic markets**

---

## Repository Structure
```text
online-retail-sales-analysis/
│
├── data/
│   └── Online Retail.xlsx
│
├── notebooks/
│   └── online_retail_analysis.ipynb
│
├── figures/
│   └── Business-ready visualizations (.png)
│
├── presentation/
│   └── Sales_Performance_Product_Strategy.pdf
│
└── README.md
