# Super-Store-EDA-and-Dashboard 🛂

## Project Description

Exploratory Data Analysis (EDA) on the Superstore sales dataset to understand business trends, profitability, customer segmentation, and factors influencing sales performance.

## Objective

To explore and analyze Superstore sales data to identify patterns, anomalies, and business insights that can enhance marketing and operational strategies.

## Goals

- Understand sales trends and profitability based on product categories, regions, and customer segments.
- Identify factors contributing to profits and losses.
- Perform customer segmentation to analyze shopping behavior.
- Provide business recommendations based on the analysis results.

## Dataset

The dataset used is from the [Superstore Sales Dataset](https://www.kaggle.com/datasets), which contains transaction information from various product categories, geographical regions, and customer segments.

## Variables Explanation

Key variables in the dataset:

- `Order ID`: Unique ID for each transaction.
- `Order Date`: Date of order placement.
- `Ship Date`: Date of product shipment.
- `Customer ID`: Unique ID of the customer.
- `Segment`: Customer segment (Consumer, Corporate, Home Office).
- `Category`: Product category (Furniture, Office Supplies, Technology).
- `Sub-Category`: Product sub-category.
- `Sales`: Total sales value from the transaction.
- `Quantity`: Number of products purchased.
- `Discount`: Discount applied to the transaction.
- `Profit`: Profit from the transaction.
- `Region`: Geographic region of the sales.

## Note

- The dataset has been cleaned and processed before analysis.
- Various data visualization techniques have been used to gain clear insights.
- The complete analysis notebook can be found in this repository.

## Exploratory Data Analysis

### **1. Sales and Revenue Analysis**

- **Total Sales per Region**  
  The Central region has the highest sales, nearly doubling the average sales of other regions.
  Meanwhile, Canada has the lowest total sales at 48,755 compared to the average of 574,511 per region.

- **Sales Trends Over Time**  
  Sales consistently increased year-over-year, indicating growing consumer demand.
  However, there is a noticeable dip in sales from November to February each year, and a recurring drop in June.

- **Best-Selling Products**  
  The most purchased product category is **Binders**, with the top-selling items being:
  - Cardinal Index Tab, Clear (326 units)
  - Avery Index Tab, Clear (252 units)
  - Ibico Index Tab, Clear (251 units)
  
  On the other hand, **Machines and Tables** have the lowest sales. This could be due to:
  1. Their long lifespan, reducing frequent purchases.
  2. Higher pricing compared to competitors.
  3. Potential quality concerns leading to lower demand.

### **2. Profitability Analysis**

- **Total Profit Per Region**  
  Canada has the highest profit margin at **24.7%**, despite lower total sales.  
  Conversely, **Southeast Asia has a negative profit margin (-0.19%)**, meaning businesses there are experiencing losses despite total sales reaching 508,774.

- **Profitability by Product Category**  
  - **Paper** has the highest profit margin.
  - **Storage** has a moderate profit margin (11.87%) despite significant revenue.
  - **Tables** have a negative profit margin (-10%), likely due to low demand and high production costs.

### **3. Customer Segmentation Analysis**

#### **Consumer Segment Dominates**

The **Consumer segment** has the highest total sales at **24,457**, making it the primary target for marketing strategies.

#### **Corporate Segment in Second Place**

The **Corporate segment** recorded total sales of **14,238**, contributing significantly but still below the Consumer segment.

#### **Home Office Segment Has the Lowest Sales**

The **Home Office segment** has the lowest total sales at **8,630**, presenting an opportunity for targeted marketing strategies to increase sales in this segment.

### **Strategic Opportunities**

To boost overall revenue, businesses can:

- **Focus on Consumer Segment:** Since it generates the highest revenue, strengthening promotions and loyalty programs for individual customers can enhance sales further.
- **Develop the Home Office Segment:** Introduce tailored product bundles or targeted marketing for remote workers.

## Business Recommendations

Based on the analysis, the following strategies are suggested:

1. **Regional Strategy:**  
   - If the goal is profitability, prioritize high-margin regions like **Canada, North Asia, and Central Asia**.
   - Evaluate pricing, operational costs, and distribution efficiency in **Southeast Asia** to address profitability issues.

2. **Customer Segmentation Focus:**  
   - Enhance marketing efforts for high-value customer segments.
   - Explore retention programs and personalized promotions for Corporate and Home Office customers.

3. **Inventory Management:**  
   - Ensure adequate stock for high-demand items like **Binders and Storage**.
   - Increase promotions for slow-selling products like **Machines and Tables**, possibly through bundling or improved quality.

4. **Cost Reduction Strategies:**  
   - Negotiate with suppliers to lower production costs.
   - Optimize supply chain efficiency to reduce unnecessary expenses.

5. **Product Promotion:**  
   - For **Tables (negative profit margin)**, consider **bundling promotions** with chairs or complementary products.
   - Improve product quality to increase customer trust and demand.

6. **Seasonal Sales Strategy:**  
   - Launch targeted promotions in **June** to counter the recurring sales dip.
   - Implement end-of-year campaigns such as **End-Year Sale or Christmas Sale** to boost sales from **November to February**.

## Dashboard

![image.png](attachment:8a32df3c-9b50-4891-8f22-f3d3e4c650c0:image.png)

The Dashboard provides an overview of Sales Performance, helping stakeholders make data-driven decisions.

# Thank You!

