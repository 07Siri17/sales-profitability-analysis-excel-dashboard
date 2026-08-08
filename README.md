
# Sales & Profitability Analysis Dashboard | Excel

An interactive Excel dashboard built to analyze sales performance, profitability, product contribution, customer segments, sales channels, categories, regions, and monthly profit trends.

The project transforms transaction-level sales data into an executive-style dashboard that helps identify the major drivers of revenue and profit and highlights areas requiring further investigation.

---

## 🎯 Business Objective

The objective of this project is to analyze sales and profitability data and provide a consolidated view of business performance.

The dashboard answers key business questions such as:

- How much revenue and profit did the business generate?
- Which products contribute the most profit?
- Which categories drive profitability?
- How does profit change over time?
- Which customer segments generate the highest profit?
- Which sales channel performs better?
- How is profitability distributed across regions?
- Which products and categories should receive greater business attention?

---

## 📁 Dataset

The workbook contains transaction-level sales data with the following fields:

| Column | Description |
|---|---|
| Date | Transaction date |
| Customer Segment | Customer type |
| Product | Product sold |
| Units | Number of units sold |
| Category | Product category |
| Sales Channel | Online or Retail |
| Region | Sales region |
| Revenue | Revenue generated |
| Cost | Cost associated with the transaction |
| Profit | Revenue minus Cost |

The dataset contains **490 transaction records** covering **January–December 2025**.

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Excel formulas
- Data aggregation
- Data visualization
- Business analysis

---

## 📌 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | ₹7,49,907.25 |
| Total Cost | ₹4,87,142.99 |
| Total Profit | ₹2,62,764.26 |
| Average Units per Transaction | 10.14 |
| Overall Profit Margin | 35.04% |

---

## 📈 Dashboard Analysis

### 1. Profit Trend

Monthly profit remains relatively stable during most of the year, with fluctuations across individual months.

The strongest month was:

**December — ₹41,587.05 profit**

The lowest month was:

**April — ₹15,075.37 profit**

December generated substantially higher profit than the rest of the year and represents an important period for further investigation.

---

### 2. Profit by Product

**Product D** is the strongest-performing product.

| Product | Profit |
|---|---:|
| Product D | ₹1,24,532.57 |
| Product E | ₹50,333.50 |
| Product B | ₹45,808.02 |
| Product A | ₹21,900.76 |
| Product C | ₹20,189.41 |

Product D contributes approximately **47.4% of total profit**, making it the dominant product in the portfolio.

---

### 3. Profit by Category

The **Tech** category generates the highest profit.

| Category | Profit |
|---|---:|
| Tech | ₹1,46,433.33 |
| Furniture | ₹96,141.52 |
| Office Supplies | ₹20,189.41 |

Tech contributes approximately **55.7% of total profit**.

---

### 4. Profit by Customer Segment

The **Corporate** segment generates the highest profit, followed closely by Small Business customers.

| Customer Segment | Profit |
|---|---:|
| Corporate | ₹96,009.88 |
| Small Business | ₹92,006.88 |
| Consumer | ₹74,747.50 |

The relatively close performance between Corporate and Small Business segments suggests that both segments are important contributors to overall profitability.

---

### 5. Profit by Sales Channel

Retail generates more profit than Online sales.

| Sales Channel | Profit |
|---|---:|
| Retail | ₹1,46,289.47 |
| Online | ₹1,16,474.79 |

Retail contributes approximately **55.7% of total profit**, compared with **44.3% from Online**.

---

### 6. Profit by Region

Profit is relatively balanced across the four regions.

| Region | Profit |
|---|---:|
| North | ₹71,486.32 |
| South | ₹65,071.53 |
| East | ₹64,925.56 |
| West | ₹61,280.85 |

The **North region** has the highest profit contribution, while the **West region** records the lowest.

However, the regional difference is not large enough to suggest a major regional performance gap.

---

## 💡 Key Business Insights

### Product concentration

Product D generates approximately **47% of total profit**, making profitability highly dependent on this product.

This is both an opportunity and a risk.

The business should continue leveraging Product D's strong performance while monitoring whether excessive dependence on one product creates portfolio risk.

### Category concentration

Tech contributes approximately **56% of total profit**, significantly ahead of Office Supplies.

This indicates that Tech products are the primary profitability driver.

### Strong retail contribution

Retail contributes approximately **56% of total profit**, indicating that the physical/retail channel currently outperforms the online channel in absolute profit.

However, this does not automatically mean Retail is more efficient. Further analysis of transaction volume, customer acquisition cost, order value, and channel-specific margins would be required before reallocating investment.

### December profit spike

December profit reached **₹41,587.05**, substantially above most other months.

This could indicate seasonality, increased demand, promotional activity, or changes in product mix.

Further investigation should be performed rather than assuming December performance will automatically repeat.

### Balanced regional performance

The four regions contribute relatively similar amounts of profit.

North leads with ₹71.5K while West generates ₹61.3K, suggesting that regional performance is broadly balanced.

---

## 🔍 Dashboard Features

The dashboard includes:

- Total Revenue KPI
- Total Profit KPI
- Average Units KPI
- Top Product KPI
- Total Cost KPI
- Monthly Profit Trend
- Profit by Product
- Profit by Category
- Profit by Customer Segment
- Profit by Sales Channel
- Region slicer/filter
- Executive-level business insights

---

## ⚙️ Project Workflow

```text
Raw Transaction Data
        ↓
Data Validation & Preparation
        ↓
Calculated Profit
        ↓
Pivot Tables
        ↓
KPI Calculations
        ↓
Pivot Charts
        ↓
Interactive Filters / Slicers
        ↓
Executive Dashboard
        ↓
Business Insights
