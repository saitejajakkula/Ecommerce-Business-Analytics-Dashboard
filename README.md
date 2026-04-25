# Ecommerce-Business-Analytics-Dashboard
👉 Analysis of global e-commerce data to identify profit drivers, discount impact, and business performance insights.

# 📊 **PROJECT REPORT**

## **Global E-Commerce Profitability & Sales Performance Analysis**

---

# **1. Business Problem**

An E-commerce company selling multiple product categories across global regions is experiencing inconsistent profitability.

While revenue appears strong, profits fluctuate significantly across product categories, sales channels, and discount strategies.

Management wants to understand:

* Which product categories generate the most profit
* Whether discount strategies are hurting margins
* Which sales channels perform best
* If marketing spend is generating profitable returns
* Which regions contribute the most revenue and profit

---

# **2. Business Objective**

The goal of this project is to:

* Identify high-profit and low-profit product categories
* Analyze the impact of discounts on profit margin
* Evaluate marketing spend efficiency
* Compare performance across sales channels (Online, Retail, Marketplace)
* Identify top-performing regions

---

# **3. Dataset Overview**

* Dataset size: **5,000 orders**
* Scope: Global e-commerce transactions
* Includes revenue, cost, discount, marketing, and regional data

---

# **4. KPI Analysis Based on the Dataset**

## **4.1 Total Revenue**

* **Value:** $5,572,100

**Insight:**
The company generated $5.57M in total sales revenue across all regions, product categories, and sales channels.
This indicates strong sales volume, but revenue alone does not guarantee profitability. Therefore, analyzing cost structure and discount strategy is important.

---

## **4.2 Total Profit**

* **Value:** $993,107

**Insight:**
The business generated nearly $1M in total profit.
Although revenue is high, cost factors such as COGS, marketing spend, and discounts significantly affect margins.
This indicates an opportunity to optimize operational efficiency and pricing strategy.

---

## **4.3 Profit Margin**

* **Value:** 17.8%

**Insight:**
For every $100 in revenue, the company keeps about $17.8 as profit.
While acceptable, there is potential to improve profitability by reducing excessive discounts and optimizing marketing spend.

---

## **4.4 Average Order Value (AOV)**

* **Value:** $1,114 per order

**Insight:**
Customers spend a relatively high amount per transaction.
This suggests multiple units or high-value purchases.
Increasing AOV through bundling, upselling, and cross-selling can boost revenue further.

---

## **4.5 Average Discount Rate**

* **Value:** 13.5%

**Insight:**
Discounting helps demand but can erode margins.
Further evaluation is needed to see if discounts actually increase revenue proportionally.

---

## **4.6 Marketing ROI**

* **Value:** 8.03x

**Insight:**
For every $1 spent on marketing, $8.03 revenue is generated.
Marketing is effective, but optimization across channels can improve returns further.

---

## **4.7 Product Category Performance**

**Insight:**

* Sports and Clothing → Top performers (revenue + profit)
* Home → Lowest profitability

---

## **4.8 Sales Channel Performance**

**Insight:**

* Marketplace → Highest revenue
* Retail → Highest profit
* Online → Lower profitability

---

## **4.9 Regional Performance**

**Insight:**

* Europe → Strongest market
* Asia → Lowest profit

---

# **5. Data Requirements**

## **5.1 Order Data**

* Order_ID, Order_Date
  **Purpose:** Track transactions and trends

## **5.2 Market Data**

* Region
  **Purpose:** Compare regional performance

## **5.3 Product Data**

* Category
  **Purpose:** Identify top categories

## **5.4 Sales Channel Data**

* Sales_Channel
  **Purpose:** Compare Online, Retail, Marketplace

## **5.5 Sales Volume**

* Units_Sold
  **Purpose:** Measure demand

## **5.6 Pricing**

* Unit_Price
  **Purpose:** Analyze pricing impact

## **5.7 Discount Data**

* Discount_%
  **Purpose:** Evaluate margin impact

## **5.8 Revenue**

* Revenue
  **Purpose:** Measure total sales

## **5.9 Cost Data**

* COGS_per_unit, Total_COGS
  **Purpose:** Analyze expenses

## **5.10 Marketing**

* Marketing_Spend
  **Purpose:** Evaluate ROI

## **5.11 Profitability**

* Profit, Profit_Margin_%
  **Purpose:** Measure financial performance

---

# **6. Core Data Analysis**

## **6.1 High Sales but Low Profit Categories**

**Insight:**

* Sports & Clothing → High revenue and profit
* Electronics & Home → Lower profit vs revenue

**Example:**

* Electronics Revenue: $1.09M
* Profit: $188K

**Interpretation:**
Higher costs or aggressive discounting reduce margins.

---

## **6.2 Underperforming Regions**

**Insight:**

* Europe → Most profitable
* Asia → Lowest profit

**Interpretation:**
Possible reasons: logistics, marketing cost, heavy discounts.

---

## **6.3 Impact of Discounts**

**Evidence:**

* Avg discount: 13.53%
* 20–30% discounts → Low or negative profit

**Example:**

* 30% discount → Profit = -$355

**Conclusion:**
Heavy discounting destroys margins.

---

## **6.4 Most Profitable Channel**

**Insight:**

* Marketplace → Highest revenue
* Retail → Highest profit
* Online → Lowest profit

---

## **6.5 Marketing Effectiveness**

* Total Revenue: $5,572,100
* Marketing Spend: ≈ $694K
* ROI: 8.03x

**Conclusion:**
Marketing is efficient but can be optimized.

---

# **7. Final Analyst Conclusion**

The company generates strong revenue ($5.57M) with $993K profit and 17.8% margin.

However, profitability is affected by:

* Discount-heavy orders
* Low margins in Electronics and Home
* Regional inefficiencies

---

# **8. Business Insights**

## **8.1 Discounts Reduce Profit**

Aggressive discounting increases sales but reduces profitability.

## **8.2 Electronics = High Revenue, Low Profit**

Likely due to cost, logistics, or discounts.

## **8.3 Sports & Clothing = Best Categories**

Strong demand and margins.

## **8.4 Retail Channel = Highest Profit**

Better margins than marketplace.

## **8.5 Asia = Low Profit Region**

Due to costs, discounts, or inefficiencies.

## **8.6 Marketing = Strong ROI**

Focus on optimization, not reduction.

---

# **9. Strategic Recommendations**

## **9.1 Optimize Discount Strategy**

* Use targeted discounts
* Avoid blanket promotions

**Impact:** Better margins

---

## **9.2 Focus on High-Profit Categories**

* Invest in Sports & Clothing
* Increase marketing

**Impact:** Higher profitability

---

## **9.3 Improve Electronics & Home**

* Reduce costs
* Optimize pricing

**Impact:** Better margins

---

## **9.4 Strengthen Retail Channel**

* Expand direct sales
* Reduce marketplace dependency

**Impact:** Higher profit retention

---

## **9.5 Improve Regional Performance**

* Optimize Asia pricing & logistics

**Impact:** Better regional profits

---

## **9.6 Optimize Marketing Spend**

* Focus on high-ROI channels

**Impact:** Improved efficiency

---

# **10. Final Business Conclusion**

The company demonstrates strong revenue performance, but profitability is influenced by:

* Discount strategies
* Cost structure
* Regional efficiency

By optimizing pricing, marketing, product focus, and sales channels, the business can significantly improve profit margins and long-term growth.

