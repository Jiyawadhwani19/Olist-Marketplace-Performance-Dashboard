# Olist Marketplace Performance & Operations Dashboard

# Power BI Dashboard

[Download Olist Power BI Dashboard](https://drive.google.com/file/d/1WRoeDoI4FjR6KWPVVOoTI6r-NWfd36ut/view?usp=sharing)

## Project Overview

This project presents a Power BI dashboard developed to analyze the performance and operational health of Olist, a Brazilian e-commerce marketplace connecting independent sellers with customers across Brazil.

The dashboard provides insights into sales performance, delivery operations, customer behavior, product categories, and customer satisfaction across the available 2016–2018 data.

---

## Business Problem

Olist's marketplace data is distributed across multiple related datasets covering orders, customers, sellers, products, payments, reviews, and logistics.

The objective of this project was to consolidate and analyze this data in Power BI to provide leadership with an interactive view of:

* Revenue and order performance
* Customer satisfaction
* Delivery and logistics performance
* Customer behavior
* Product category performance
* State-level marketplace performance

---

## Dataset

The project uses multiple Olist datasets containing information about:

* Orders
* Order Items
* Order Payments
* Order Reviews
* Products
* Customers
* Sellers
* Geolocation
* Product Category Translation

The datasets cover marketplace activity across Brazil during 2016–2018.

---

## Tools & Technologies

* **Power BI** – Dashboard development and data visualization
* **Power Query** – Data cleaning and transformation
* **Excel** – Source datasets and category translation
* **DAX** – Measures and KPI calculations

---

## Dashboard Pages

### 1. Overview

Provides an overall view of marketplace performance through key metrics including:

* Total Revenue
* Average Delivery Delay
* Average Review Score
* Total Orders
* Revenue by Customer State
* Average Review Score by Delivery Delay Bucket
* Product Category Performance

### 2. Logistics

Focuses on delivery and seller-side operational performance, including:

* Freight-to-Price Ratio
* On-Time Delivery Rate
* State-level logistics performance

### 3. Customers

Analyzes customer behavior through:

* Total Unique Customers
* Repeat Purchase Rate
* One-Time vs Repeat Customers

Interactive filters are provided for relevant dimensions such as year and customer state.

---

## Data Preparation

The source data required preparation before analysis. Data from multiple tables was combined using relationships and Power Query transformations.

Key preparation activities included:

* Combining related datasets
* Handling incomplete or inconsistent fields
* Mapping product category names from Portuguese to English
* Preparing date-related fields for analysis
* Creating calculated measures and KPIs
* Organizing the data model for dashboard reporting

---

## Key KPIs

The dashboard tracks several important marketplace KPIs, including:

| KPI                    | Purpose                                          |
| ---------------------- | ------------------------------------------------ |
| Total Revenue          | Measures overall marketplace sales value         |
| Total Orders           | Measures order volume                            |
| Average Delivery Delay | Evaluates delivery performance                   |
| Average Review Score   | Measures customer satisfaction                   |
| Freight-to-Price Ratio | Evaluates freight cost relative to product price |
| On-Time Delivery Rate  | Measures delivery reliability                    |
| Total Unique Customers | Measures customer reach                          |
| Repeat Purchase Rate   | Measures customer retention                      |

---

## Key Insights

Based on the dashboard:

* Total revenue is approximately **12.43M** across approximately **99K orders**.
* The average delivery delay is approximately **11.88 days**.
* The average review score is approximately **4.09 out of 5**.
* Approximately **96K unique customers** are represented in the dashboard.
* The repeat purchase rate is approximately **3.12%**, indicating that the majority of customers are one-time purchasers.
* Logistics performance varies across states, including differences in freight-to-price ratio and on-time delivery rate.

---

## Business Recommendations

The analysis can support decisions such as:

* Identifying states with weaker delivery performance
* Monitoring freight costs relative to product prices
* Improving delivery reliability in underperforming regions
* Investigating factors affecting customer satisfaction
* Developing strategies to increase repeat purchases
* Identifying high-performing product categories and regions

---

## Data & Maintenance Considerations

The dashboard depends on multiple interconnected datasets. Changes to source file names, column names, data types, or table structures could affect Power Query transformations, relationships, and dashboard calculations.

For recurring use, the data-refresh process should be standardized so that new data can be added without changing the overall dashboard structure.

A maintainable workflow would include:

1. Collecting updated source data
2. Validating the incoming files
3. Refreshing Power Query transformations
4. Checking relationships and calculated measures
5. Validating key KPIs
6. Refreshing the Power BI dashboard
7. Reviewing visuals for unexpected changes

---

## Repository Structure

```text
Olist-Marketplace-Performance-Dashboard/
│
├── Dashboard Preview/
│   ├── Customers.png
│   ├── Logistics.png
│   └── Overview.png
│
├── Datasets/
│   ├── olist_customers_dataset.csv
│   ├── olist_geolocation_dataset.zip
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
│
├── Olist_Dashboard_Case_Study.pptx
└── README.md
---



## Project Objective

The overall objective of this project was to transform multiple Olist marketplace datasets into an interactive Power BI reporting solution that provides meaningful insights into marketplace performance, logistics, and customer behavior.
