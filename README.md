# **PROJECT NAME**

**Global E-Commerce Profitability & Sales Performance Analysis**
<img width="1895" height="596" alt="Screenshot (209)" src="https://github.com/user-attachments/assets/6fb16cca-f676-4b50-8fbe-2e35f8436e7d" />

---

## **Business Problem**

An e-commerce company selling multiple product categories across global regions is experiencing inconsistent profitability.

While revenue appears strong, profits fluctuate significantly across product categories, sales channels, and discount strategies.

Management wants to understand:

* Which product categories generate the most profit
* Whether discount strategies are hurting margins
* Which sales channels perform best
* If marketing spend is generating profitable returns
* Which regions contribute the most revenue and profit

---

## **Business Objective**

The goal of this project is to:

* Identify high-profit and low-profit product categories
* Analyze the impact of discounts on profit margin
* Evaluate marketing spend efficiency
* Compare performance across sales channels (Online, Retail, Marketplace)
* Identify top-performing regions

---

## **KPI Analysis Based on the Dataset**
<img width="1896" height="178" alt="Screenshot (198)" src="https://github.com/user-attachments/assets/a49d5887-9355-44bb-a286-d46b03c8eeae" />

### **1. Total Revenue**

Value: $5,572,100

Insight:
The company generated $5.57M in total sales revenue across all regions, product categories, and sales channels.

This indicates strong sales volume, but revenue alone does not guarantee profitability. Therefore, analyzing cost structure and discount strategy is important to understand overall financial performance.

---

### **2. Total Profit**

Value: $993,107

Insight:
The business generated nearly $1M in total profit from its operations.

Although revenue is high, the profit level suggests that cost factors such as COGS, marketing spend, and discounts significantly affect margins.

This indicates an opportunity to optimize operational efficiency and pricing strategy.

---

### **3. Profit Margin**

Value: 17.8%

Insight:
The overall profit margin of the business is 17.8%.

This means that for every $100 in revenue, the company keeps about $17.8 as profit.

While this margin is acceptable for many e-commerce businesses, there is potential to improve profitability by reducing excessive discounts and optimizing marketing spend.

---

### **4. Average Order Value (AOV)**

Value: $1,114 per order

Insight:
Customers spend an average of $1,114 per transaction.

A relatively high AOV suggests that customers tend to purchase multiple units or higher-priced products, contributing positively to revenue growth.

Increasing AOV further through bundling, upselling, and cross-selling strategies could significantly improve revenue.

---

### **5. Average Discount Rate**

Value: 13.5%

Insight:
The company provides an average discount of 13.5% across orders.

While discounts help stimulate demand, excessive discounting can erode profit margins.

Further analysis should evaluate whether higher discount levels actually lead to proportional increases in revenue.

---

### **6. Marketing ROI**

Value: 8.03x

Insight:
For every $1 spent on marketing, the company generates approximately $8.03 in revenue.

This indicates strong marketing efficiency, suggesting that marketing investments are effectively driving sales.

However, further analysis could determine which channels or campaigns deliver the highest ROI.

---

## **7. Product Category Performance**

Revenue by Category:

Sports: $1.16M
Clothing: $1.16M
Beauty: $1.12M
Electronics: $1.09M
Home: $1.04M

Profit by Category:

Sports: $213K
Clothing: $208K
Beauty: $199K
Electronics: $188K
Home: $183K

Insight:
Sports and Clothing are the top-performing categories in both revenue and profit.

Home shows the lowest profitability, suggesting possible issues with pricing, costs, or discount strategies.

---

## **8. Sales Channel Performance**

Revenue by Channel:

Marketplace: $1.90M
Online: $1.84M
Retail: $1.83M

Profit by Channel:

Retail: $360K
Marketplace: $350K
Online: $282K

Insight:
Marketplace generates the highest revenue.
Retail generates the highest profit.
Online has lower profitability, indicating higher marketing or operational costs.

---

## **9. Regional Performance**

Revenue by Region:

Europe: $1.16M
South America: $1.14M
MEA: $1.10M
North America: $1.09M
Asia: $1.07M

Profit by Region:

Europe: $216K
MEA: $198K
North America: $197K
South America: $197K
Asia: $183K

Insight:
Europe is the strongest market in both revenue and profit.
Asia generates the lowest profit, suggesting cost inefficiencies or pricing issues.

---

## **Summary of Key KPIs**

Total Revenue: $5.57M
Total Profit: $993K
Profit Margin: 17.8%
Average Order Value: $1,114
Average Discount: 13.5%
Marketing ROI: 8.03x

---

## **Data Requirements**

### **1. Order / Transaction Data**

Columns used: Order_ID, Order_Date
Why needed: Identify each transaction uniquely and analyze sales trends over time.

### **2. Market / Geographic Data**

Columns used: Region
Why needed: Compare sales performance across regions.

### **3. Product Category Data**

Columns used: Category
Why needed: Identify top-performing categories.

### **4. Sales Channel Data**

Columns used: Sales_Channel
Why needed: Evaluate performance across Online, Retail, and Marketplace.

### **5. Sales Volume Data**

Columns used: Units_Sold
Why needed: Measure demand and volume trends.

### **6. Pricing Data**

Columns used: Unit_Price
Why needed: Understand pricing impact.

### **7. Discount Data**

Columns used: Discount_%
Why needed: Analyze effect on margins.

### **8. Revenue Data**

Columns used: Revenue
Why needed: Measure total performance.

### **9. Cost Data**

Columns used: COGS_per_unit, Total_COGS
Why needed: Analyze cost and profitability.

### **10. Marketing Data**

Columns used: Marketing_Spend
Why needed: Evaluate marketing efficiency.

### **11. Profitability Data**

Columns used: Profit, Profit_Margin_%
Why needed: Measure financial performance.

---

## **Final Dataset Structure**

Transaction Data: Order_ID, Order_Date
Market Data: Region
Product Data: Category
Channel Data: Sales_Channel
Sales Volume: Units_Sold
Pricing: Unit_Price
Discounts: Discount_%
Revenue: Revenue
Cost: COGS_per_unit, Total_COGS
Marketing: Marketing_Spend
Profitability: Profit, Profit_Margin_%

---

## **Core Data Analysis**
<img width="1881" height="883" alt="Screenshot (199)" src="https://github.com/user-attachments/assets/d2ce6e2d-2011-4cc9-a89e-ca0abaf0488a" />
<img width="1873" height="120" alt="Screenshot (201)" src="https://github.com/user-attachments/assets/d1ecb553-a7b8-4044-91c1-366a2cbde7c1" />

1. Electronics and Home generate lower profit compared to revenue → Indicates high costs or discounting.
<img width="1873" height="629" alt="Screenshot (202)" src="https://github.com/user-attachments/assets/666fe0df-7011-4f6a-833f-cab4b1437a36" />

2. Asia is the lowest-performing region → Suggests inefficiencies.
<img width="1894" height="620" alt="Screenshot (208)" src="https://github.com/user-attachments/assets/419bbb13-56e9-4cd2-8532-bb49af22e428" />

<img width="1877" height="505" alt="Screenshot (203)" src="https://github.com/user-attachments/assets/c58c0a00-c41d-48b2-8519-c2ac342d411b" />

4. High discounts (20–30%) reduce profit → Some orders even negative.

5. Retail channel is most profitable → Direct sales are stronger.

6. Marketing ROI is strong (8.03x) → Efficient but can be optimized.

---

## **Final Analyst Conclusion**

The company generates strong global revenue ($5.57M) with $993K profit and a 17.8% margin.

However, profitability is affected by discount-heavy orders, lower margins in Electronics and Home, and regional inefficiencies.

Focusing on high-performing categories, strengthening retail channels, and optimizing discount strategies can significantly improve profitability.

---

## **Business Insights**
<img width="1893" height="240" alt="Screenshot (210)" src="https://github.com/user-attachments/assets/918504d2-42cc-42e7-ba14-4f93aa074b37" />

* Discounts reduce profit margins
* Electronics has lower profitability
* Sports and Clothing are strong profit drivers
* Retail channel gives highest profit
* Asia has lower profitability
* Marketing ROI is strong

---

## **Strategic Recommendations**
<img width="1878" height="640" alt="Screenshot (205)" src="https://github.com/user-attachments/assets/3fdad6dd-cc95-4616-b6ef-8b94ebd7721b" />

* Optimize discount strategy
* Focus on high-profit categories
* Improve Electronics & Home margins
* Strengthen Retail channel
* Improve Asia strategy
* Optimize marketing allocation
<img width="1878" height="403" alt="Screenshot (204)" src="https://github.com/user-attachments/assets/d36b619c-e370-4e10-b1e7-eb567379e49a" />

---

## **Final Business Conclusion**

The company demonstrates strong revenue performance, but profitability depends on pricing, cost structure, and regional efficiency.

By optimizing these factors, the business can significantly improve profit margins and long-term growth.

