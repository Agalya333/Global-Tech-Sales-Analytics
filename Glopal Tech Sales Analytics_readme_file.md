# Global Tech Sales Analysis 📊💻

A comprehensive end-to-end data analytics project focused on analyzing global technology product sales performance, uncovering customer purchasing patterns, and providing actionable business recommendations through statistical analysis and an interactive Power BI dashboard.

\---

## 📑 Table of Contents

1. [Project Overview](#-project-overview)
2. [Domain \& Problem Statement](#-domain--problem-statement)
3. [Dataset Description](#-dataset-description)
4. [Tech Stack \& Tools](#-tech-stack--tools)
5. [End-to-End Workflow](#-end-to-end-workflow)

   * [Data Cleaning \& Preprocessing](#1-data-cleaning--preprocessing)
   * [Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
   * [Statistical Analysis](#3-statistical-analysis)
   * [Interactive Dashboard Development](#4-interactive-dashboard-development)
6. [Key Business Insights](#-key-business-insights)
7. [Conclusion ](#-conclusion--recommendations)

\---

## 🌐 Project Overview

The **Global Tech Sales Analysis** project explores retail and e-commerce transaction data across worldwide store locations. By leveraging Python for data cleaning and exploratory data analysis (EDA) alongside Power BI for visual analytics, this project identifies revenue drivers, peak seasonal purchasing trends, and payment/shipping preferences of global technology consumers.

\---

## 🎯 Domain \& Problem Statement

* **Domain:** Retail \& E-commerce (Technology Sector)
* **Problem Statement:** Retail businesses often struggle with fragmented sales insights, unclear geographical demand patterns, and unoptimized inventory during seasonal fluctuations. This project bridges that gap by transforming raw sales transaction logs into interactive visual dashboards and data-backed business strategies.

\---

## 📁 Dataset Description

* **Dataset Name:** `global\\\_tech\\\_sales\\\_2026.csv`
* **Record Count:** 5,000 sales transactions
* **Attributes (20 Columns):**

  * **Transaction Details:** `order\\\_id`, `order\\\_month`, `transaction\\\_date`
  * **Product Information:** `product\\\_category`, `product\\\_name`, `unit\\\_price\\\_usd`
  * **Customer \& Demographics:** `customer\\\_id`, `customer\\\_rating`, `gender`
  * **Location \& Channel:** `store\\\_location` (New York, London, Berlin, Dubai, Tokyo, Sydney, Singapore, Toronto), `sales\\\_channel`
  * **Order Metrics:** `quantity`, `total\\\_amount\\\_usd`
  * **Fulfillment:** `payment\\\_method` (Credit Card, PayPal, Debit Card, Apple Pay, Google Pay), `shipping\\\_type` (Standard, Express, Same-Day)

\---

## 🛠️ Tech Stack \& Tools

* **Programming Language:** Python 3.x
* **Data Manipulation \& Analysis:** Pandas, NumPy
* **Data Visualization (Python):** Matplotlib, Seaborn
* **Business Intelligence Tool:** Power BI Desktop
* **Version Control:** Git \& GitHub

\---

## 🔄 End-to-End Workflow

### 1\. Data Cleaning \& Preprocessing

* Checked for missing values (`df.isnull().sum()`) and duplicate entries (`df.duplicated().sum()`).
* Fixed data types (converted dates to datetime objects and prices/totals to numeric floats).
* Cleaned text attributes, removed unwanted special characters, and standardized categorical labels across all columns.

### 2\. Exploratory Data Analysis (EDA)

* Analyzed distribution profiles of key metrics like `total\\\_amount\\\_usd` and `customer\\\_rating`.
* Evaluated sales distribution across store locations, product categories, and payment channels.
* Generated boxplots for outlier detection to isolate unusual high-value sales transactions.

### 3\. Statistical Analysis

* **Summary Metrics:** Calculated mean, median, standard deviation, IQR, and percentiles for numerical variables.
* **Skewness Analysis:** Measured data symmetry; identified positive skewness in sales totals due to high-value purchases.
* **Kurtosis Analysis:** Evaluated the peak and tail weight of the sales distribution to identify transaction volatility and extreme values.

### 4\. Interactive Dashboard Development (Power BI)

* **Store Location Map Visual:** Geospatial mapping displaying global revenue distribution across key international hub cities.
* **Monthly Sales Trend (Line Chart):** Tracks revenue changes across order months to highlight seasonal peaks and demand drops.
* **Payment \& Shipping Visuals (Donut/Stacked Bar Charts):** Analyzes preference distributions across payment options (Credit Card, PayPal, etc.) and shipping preferences.
* **Revenue vs. Pricing (Scatter Plot):** Explores the correlation between product unit price and overall revenue generated.

\---

## 💡 Key Business Insights

* **Revenue Drivers:** Revenue is heavily concentrated in major urban store locations (such as New York, London, Berlin, and Dubai) and top-performing product categories (Smartphones and Computers).
* **Customer Preferences:** Customers predominantly prefer digital payment methods (Credit Cards and PayPal) and standard shipping options over express services.
* **Seasonal Trends:** Outlier and trend analyses successfully highlight peak sales periods, providing actionable indicators for targeted marketing and inventory planning.

\---

## 🏁 Conclusion 

1. **Inventory Optimization:** Scale up inventory levels for high-performing product categories (Smartphones, Laptops) prior to peak sales months identified in the trend analysis.
2. **Geographical Focus:** Focus regional marketing budgets and promotional campaigns on top-revenue urban hubs (New York, London, Dubai).
3. **Digital Checkout Enhancement:** Optimize online checkout workflows specifically for Credit Card and PayPal users to maintain high conversion rates.

\---

## 

