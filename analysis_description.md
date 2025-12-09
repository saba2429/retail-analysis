# Retail Sales Data Analysis – Detailed Documentation

## Project Overview
This project analyzes retail sales data to understand customer buying behaviour, product trends, and seasonal patterns. The analysis aims to provide actionable insights for marketing and sales strategy.

## Data Description
The dataset contains transaction-level sales data with customer demographics.  

**Columns:**
- **customer_id** – unique identifier for each customer
- **gender** – Male/Female
- **age** – customer age
- **prod_category** – category of the product purchased
- **quantity** – number of units purchased
- **per_unit_price** – price per unit
- **total_amount** – quantity × per_unit_price
- **Month** – month of purchase
- **Month number** – numeric month for chronological sorting
- **Age group** – bucketed age ranges (e.g., 18–25, 26–35, etc.)

Additional columns (`Month`, `Month number`, `Age group`) were added to support pivot table analysis.

## Analysis Steps

### Sales by Gender
- Created a pivot table to calculate total sales (`total_amount`) by `gender`
- Visualized the distribution with a bar chart
- **Objective:** Identify which gender contributes more to overall sales
- **Observation:** Female customers contributed **51%** of revenue, Male **49%**

### Revenue by Product Category
- Pivot table to sum `total_amount` grouped by `prod_category`
- Visualized with a Pie chart to understand the highest-selling category
- **Objective:** Understand which product categories generate the most revenue
- **Observation:** Electronics generated the highest revenue, followed by Clothing and Beauty

### Sales by Age Group
- Pivot table summing `total_amount` by `Age group`
- Visualized with a bar chart
- **Objective:** Identify high-value customer segments
- **Observation:** Customers aged 46+ generated the highest revenue

### Sales by Month
- Pivot table summing `total_amount` by `Month`
- Visualized with a Pie chart to understand the highest-selling month
- **Objective:** Understand seasonal patterns and peak months
- **Observation:** October was the highest-selling month, followed by February and December

## Key Insights
- Gender distribution: Female customers contributed 51% of revenue, Male 49%
- Top product categories: Electronics generated the highest revenue, followed by Clothing and Beauty
- Most valuable age groups: Customers aged 46+ generated the highest revenue
- Seasonal trends: October was the highest-selling month, followed by February and December

## Conclusion & Recommendations

- **Gender insights:** Since female customers contribute slightly more to revenue, marketing campaigns can target them specifically for products like Beauty and Clothing.  
- **Product categories:** Focus on Electronics and Clothing for promotions and stock planning, as they generate the highest revenue.  
- **Age groups:** Customers aged 46+ are the most valuable, so loyalty programs or special offers for this group can boost sales.  
- **Seasonal trends:** Plan inventory and promotions around peak months (October, February, December) to maximize revenue.  

## Further Analysis / Future Work

With this dataset, additional analyses could include:

- **Customer segmentation:** Group customers based on total spending, frequency, or product preferences to identify high-value or loyal customers.  
- **Product performance over time:** Analyze how each product category performs month-to-month to spot seasonal trends or growth opportunities.  
- **Cross-analysis of age and product category:** Understand which age groups prefer which products to tailor marketing campaigns.  
- **Average order value and frequency:** Calculate metrics like average purchase per customer or repeat purchase rates to understand buying behaviour.  
- **Promotional impact analysis:** If promotion data is available, analyze how discounts or campaigns affect sales per category or month.  



