<h1 align="center">Coffee Shop Sales Analysis Using Python</h1>

<p align="center">
    <img src="https://github.com/meabhaykr/Coffee-Shop-Sales-Analysis-Using-SQL/blob/main/Header.png" alt="Header">
</p>


**An analytical dashboard showcasing sales performance and customer behavior insights for Maven Roasters, a fictitious coffee shop chain operating in New York City.**

---

## Table of Contents
- [Project Background](#project-background)
- [Data Structure](#data-structure)
- [Insights and Analysis](#insights-and-analysis)
  - [Overview of Findings](#overview-of-findings)
  - [Detailed Insights](#detailed-insights)
- [Recommendations](#recommendations)
- [How to Use the Dashboard](#how-to-use-the-dashboard)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [License](#license)

---

## Project Background
Maven Roasters' dataset contains 149,115 transaction records, including timestamps, store locations, and product-level details. This project aims to:
- Analyze sales performance across three NYC locations.
- Provide insights into transaction trends, product popularity, and customer preferences.
- Develop actionable strategies to optimize operations and enhance customer satisfaction.

The dashboard visualizes key metrics such as Total Revenue, Order Volume, and Average Order Value (AOV), alongside product and location-based performance analysis.

---

## Data Structure
The dataset consists of a single table (`sales`) with:
- **149,115 records** detailing customer transactions.
- Fields including `transaction_id`, `timestamp`, `store_location`, `product_name`, and `order_quantity`.

---

## Insights and Analysis

### Overview of Findings
- **Total Revenue**: $698K from 149K orders, with an AOV of $4.69.
- **Peak Month**: June ($166K revenue), attributed to increased summer foot traffic.
- **Top Store**: Hell's Kitchen ($236K revenue).
- **Top Product**: Barista Espresso ($91K sales).
- **Popular Categories**: Coffee led the way with $58K, followed by Tea ($45K) and Bakery items ($22K).

### Detailed Insights
1. **Sales by Month and Location**:
   - June: Highest revenue ($166K).
   - January: Lowest revenue, highlighting potential for seasonal promotions.

2. **Product Performance**:
   - Barista Espresso: $91K in sales.
   - Brewed Chai Tea: $77K in sales.
   - Coffee Beans had the highest AOV at $22.

3. **Customer Behavior**:
   - **Peak Hour**: 10 AM.
   - **Peak Days**: Sales consistent across weekdays (~21K orders/day).
   - **Popular Coffee Type**: Gourmet Brewed Coffee (29% of orders).

---

## Recommendations
1. **Promote High-Value Products**:
   - Implement seasonal "Buy One Get One Free" offers for Coffee Beans during colder months to boost home brewing.
   
2. **Boost Sales in Slow Months**:
   - Offer reward cards or complimentary drinks during January and February to increase customer engagement.

3. **Optimize Operating Hours**:
   - Introduce end-of-day discounts during the 8 PM slot to drive sales.

4. **Customer Feedback**:
   - Collect seasonal surveys to refine services and offerings.

---

## Dashboard
<p align="center">
    <img src="https://github.com/meabhaykr/Coffee-Shop-Sales-Analysis-Using-Python/blob/main/Dashboard Image.png" alt="Dashboard Image">
</p>

---

## Technologies Used
- **Python**: Data analysis and dashboard creation.
- **Pandas**: Data wrangling and transformation.
- **Matplotlib & Seaborn**: Data visualization.

---

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/coffee-shop-sales-dashboard.git
   ```
2. Navigate to the project folder:
   ```bash
   cd coffee-shop-sales-dashboard
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
