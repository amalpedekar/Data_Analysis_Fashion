# 👗 Fashion Retail Product Performance Analysis

## 📌 Project Overview

This project explores a fashion retail dataset to understand product performance across multiple dimensions such as pricing, customer ratings, discounts, inventory levels, and returns. The goal is to simulate real-world retail analytics and extract business insights that can help improve pricing strategies, product quality, and customer satisfaction.

Unlike traditional sales forecasting projects, this analysis focuses on **product-level performance and behavioral patterns** rather than revenue prediction.

---

## 🎯 Objectives

* Analyze pricing distribution across fashion categories and brands
* Understand the impact of discounts (markdowns) on pricing and customer behavior
* Explore customer satisfaction through ratings
* Investigate product return patterns and reasons
* Study inventory distribution across product categories
* Identify trends in purchase activity over time

---

## 📊 Dataset Description

The dataset contains fashion product records with the following features:

* `product_id` – Unique identifier for each product
* `category` – Fashion category (e.g., dresses, shoes, accessories)
* `brand` – Brand name
* `season` – Season of product release
* `size` – Product size
* `color` – Product color
* `original_price` – Initial product price
* `markdown_percentage` – Discount applied
* `current_price` – Final selling price after discount
* `stock_quantity` – Available inventory
* `customer_rating` – Customer review score
* `is_returned` – Whether the product was returned
* `return_reason` – Reason for return (if applicable)
* `purchase_date` – Date of purchase (used for time-based analysis)

---

## 🧹 Data Preparation

* Converted `purchase_date` to datetime format
* Set `purchase_date` as index for time series analysis
* Handled categorical and numerical separation
* Aggregated data for trend-based visualizations

---

## 📈 Exploratory Data Analysis

### 1. Price Distribution by Category

* Used boxplots to analyze how product prices vary across categories
* Identified premium vs budget segments

### 2. Markdown (Discount) Analysis

* Studied discount distribution across categories
* Evaluated pricing strategies used in different product groups

### 3. Customer Rating Analysis

* Distribution of ratings across all products
* Category-wise comparison of customer satisfaction

### 4. Brand Performance

* Identified brands with highest average customer ratings
* Compared brand-level performance variability

### 5. Return Analysis

* Analyzed return frequency across categories
* Investigated common return reasons
* Studied relationship between discounts and returns

### 6. Inventory Distribution

* Examined stock levels across categories
* Identified overstocked and high-demand product groups

---

## 📊 Time-Based Analysis

### Purchase Volume Over Time

* Aggregated purchases on a monthly basis
* Visualized purchase trends using line charts
* Identified fluctuations in customer demand over time

> Note: Full time series decomposition was not performed due to limited historical depth in the dataset.

---

## 📌 Key Insights

* Product pricing varies significantly across categories, with clear premium and budget segments
* Discounts are not evenly distributed and vary by product type
* Customer ratings are generally positive but differ across categories and brands
* Return behavior is influenced by product category and possibly sizing issues
* Purchase activity shows visible trends over time, indicating demand fluctuations

---

## ⚠️ Limitations

* Dataset does not include true sales metrics such as quantity sold or revenue
* Time series analysis is limited due to data range constraints
* Customer-level behavior (IDs, repeat purchases) is not available
* Decomposition analysis was not fully applicable due to dataset size

---

## 🚀 Future Improvements

* Add synthetic or real transaction-level sales data
* Build demand forecasting model
* Implement recommendation system based on product similarity
* Extend dataset with customer segmentation
* Integrate inventory forecasting for SaaS simulation

---

## 🧠 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels (for time series analysis)

---

## 📷 Sample Visualizations

* Boxplots for price and ratings
* Bar charts for brand comparison
* Count plots for return reasons
* Line charts for purchase trends

---

## 👤 Author

Amal Farhan

---
