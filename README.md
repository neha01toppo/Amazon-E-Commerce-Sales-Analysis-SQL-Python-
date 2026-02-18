# Amazon-E-Commerce-Sales-Analysis-SQL-Python-
This project analyzes Amazon e-commerce sales data related to women’s clothing categories.

## Project Overview
This project analyzes Amazon e-commerce sales data related to women’s clothing categories.
The analysis focuses on understanding order behavior, sales trends, returns, cancellations,
and revenue distribution across products, time, and states.

---

## Problem Statement
To analyze sales trends over a period of 3–4 months in women’s clothing and identify:
- Which products generate high revenue
- Where orders are placed the most
- Which products face high returns or cancellations

---

## Agenda
1. Analyze month-wise sales trends
2. Identify products with the highest returns or cancellations
3. Segment data by weekday vs weekend to understand order behavior
4. Compare revenue across product categories
5. Rank states based on revenue and order volume

---

## Dataset Description
- Source: Kaggle (Amazon E-commerce Sales Dataset)
- Dataset contains order-level data including:
  -order_id
  -date
  -status
  -fulfilment
  -sales_channel
  -ship_service_level
  -style
  -sku
  -category
  -size
  -asin
  -courier_status
  -qty
  -currency
  -amount
  -ship_city
  -ship_state
  -ship_postal_code
  -ship_country
  -promotion_ids
  -b2b

---

## Tools Used
- **Python**: Data cleaning and preprocessing
- **SQL (PostgreSQL)**: Data analysis and aggregation
- **GitHub**: Project documentation 

---

## Key Insights

### 1. Order Placement Behavior
- Weekdays have a higher number of orders compared to weekends.
- Approximately **70% of orders are placed on weekdays**, while **29% occur on weekends**.

### 2. Top-Selling Categories
- **SET** and **KURTA** categories have the highest number of orders.
- These categories contribute significantly to overall revenue.

### 3. Returns and Cancellations
- The **SET** product category has the highest number of returns or cancellations.
- High return rates indicate possible issues with product quality, size, or customer expectations.

### 4. Delivery Performance
- Around **64% of orders remain in the ‘Shipped’ status** within the 3–4 month period.
- **8% of orders are cancelled**, highlighting scope for improving delivery and fulfillment processes.
- Delivery delays negatively impact customer satisfaction and order completion.

### 5. State-wise Performance
- Certain states generate higher revenue and order volume compared to others.
- State-level ranking helps identify high-performing and low-performing regions.

---

## Recommendations

1. Create targeted offers for low-selling products and promote high-selling categories like SET and KURTA.
2. Optimize the delivery process by reducing shipping and processing time.
3. Investigate the root causes of high returns and cancellations, especially for SET products.
4. Focus marketing efforts more on weekdays, as order volume is higher during this period.
5. Improve logistics performance in underperforming states to increase order completion rates.

---

## Limitations
- The dataset does not include delivery dates, making it impossible to calculate average delivery time or analyze delivery performance.
- There is no column capturing reasons for returned products, limiting the ability to analyze return-related issues such as quality defects, delayed delivery, or customer dissatisfaction.

---

## Conclusion
This analysis highlights key sales patterns, customer say behaviors, and operational issues
within Amazon women’s clothing sales data. Implementing the above recommendations can help
reduce cancellations, improve delivery performance, and increase overall revenue.
