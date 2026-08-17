# 📊 Superstore Sales & Profitability Analysis

## 📌 Project Overview

This project presents an end-to-end analysis of the Superstore dataset to understand sales performance, profitability, discount impact, regional performance, category and sub-category performance, and loss-making transactions.

The project follows a complete data analytics workflow:

**Raw Data → Python EDA → Statistical Analysis → Business Insights → Power BI Dashboard**

Python was used for data cleaning, exploratory data analysis, statistical analysis, and identifying important business patterns. Microsoft Power BI was then used to transform these findings into an interactive business dashboard.

---

# 🎯 Business Objectives

The main objectives of this project were to:

- Analyze overall sales and profitability.
- Identify the most profitable categories and sub-categories.
- Identify loss-making categories, sub-categories, and products.
- Analyze regional sales and profitability.
- Understand the relationship between sales and profit.
- Analyze the relationship between discount and profit.
- Identify high-sales but loss-making transactions.
- Identify products contributing significantly to losses.
- Provide business recommendations based on the analysis.

---

# 🗂️ Dataset

The project uses the **Sample Superstore** transactional dataset.

The dataset contains information related to:

- Orders
- Customers
- Products
- Categories
- Sub-categories
- Sales
- Quantity
- Discount
- Profit
- Regions
- States
- Order dates

The data represents transactional sales information that can be used to analyze business performance and profitability.

---

# 🛠️ Tools & Technologies

### Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Power BI
- Data visualization
- Interactive dashboards
- DAX measures
- Calculated columns
- Filters and slicers
- Conditional formatting
- Geographic analysis

---

# 🔍 Exploratory Data Analysis

The Python EDA focused on understanding the structure and behavior of the data before creating the Power BI dashboard.

### Analysis performed:

- Dataset structure and data types
- Missing value analysis
- Duplicate analysis
- Descriptive statistics
- Category-level analysis
- Sub-category analysis
- Product-level analysis
- Regional analysis
- State-level analysis
- Customer-level analysis
- Sales analysis
- Profit analysis
- Discount analysis
- Correlation analysis
- Sales vs Profit analysis
- Identification of high-sales low-profit transactions

---

# 📈 Statistical Analysis

Correlation analysis was performed between the major numerical variables.

| Variable Relationship | Correlation |
|---|---:|
| Sales & Profit | 0.479 |
| Sales & Quantity | 0.201 |
| Sales & Discount | -0.028 |
| Quantity & Profit | 0.066 |
| Discount & Profit | -0.219 |

### Key observations

- Sales and Profit have a moderate positive relationship.
- Higher sales generally tend to be associated with higher profit, but high sales do not guarantee profitability.
- Discount and Profit have a negative relationship.
- Quantity has only a weak relationship with Profit.
- Discount has a relatively weak negative relationship with Profit, indicating that higher discounts can be associated with lower profitability.

---

# 📊 Category Analysis

The analysis showed that:

| Category | Profitability |
|---|---:|
| Technology | 15.61% |
| Office Supplies | 13.80% |
| Furniture | 3.88% |

### Key Insight

**Technology was the strongest-performing category in terms of profitability**, while Furniture had considerably lower profitability.

This indicates that category-level sales alone are not sufficient to evaluate business performance. Profitability should also be considered.

---

# 🔎 Sub-Category Analysis

Sub-category analysis revealed that some sub-categories were responsible for significant losses.

Major loss-making sub-categories identified included:

- Tables
- Machines
- Binders
- Bookcases
- Chairs

### Key Insight

Although an overall category may generate profit, individual sub-categories within that category can still generate significant losses.

This makes sub-category-level analysis important for identifying the actual sources of poor profitability.

---

# 🌎 Regional Analysis

Regional analysis showed significant differences in profitability.

The analysis identified:

- East as one of the largest contributors to losses in loss-making transactions.
- Central as another major contributor to losses.
- West showed comparatively better profitability in the overall analysis.

Regional performance was also analyzed at the state level to identify states contributing to losses.

### Key Insight

Profitability varies significantly across geographical regions and states, indicating that regional performance should be considered when making pricing and discount decisions.

---

# 💰 High-Sales Low-Profit Analysis

A specific analysis was performed to identify transactions where:

**Sales > 75th percentile of Sales**

AND

**Profit < 0**

These transactions were classified as:

**High-Sales Loss-Making Transactions**

This helped identify situations where the business generated relatively high revenue but still lost money.

### Key Insight

High sales do not necessarily mean a successful transaction.

Some transactions generated substantial sales while still producing negative profit.

---

# 🏷️ Discount Analysis

The average discount for high-sales loss-making transactions was approximately:

**34.23%**

while the overall average discount was approximately:

**15.62%**

### Key Insight

High-sales loss-making transactions had a substantially higher average discount than the overall dataset.

This suggests that aggressive discounting may be an important factor contributing to profitability problems and should be investigated further.

---

# 🛍️ Product-Level Analysis

Product-level analysis was performed to identify:

- Highest-profit products
- Loss-making products
- Top loss-making products
- High-sales low-profit products

The analysis showed that some products could generate significant sales while still producing negative profit.

### Key Insight

Product-level profitability is important because individual loss-making products can reduce the overall profitability of a category.

---

# 📊 Power BI Dashboard

The analysis was converted into an interactive Power BI dashboard consisting of two pages.

---

## Page 1 — Sales & Profitability Overview

The first page provides a high-level overview of business performance.

### Key visuals include:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Profit Percentage
- Sales and Profit trends
- Profit by Category
- Profit by Sub-category
- Regional performance
- State-level geographic analysis

### Purpose

This page allows management to quickly understand overall business performance and identify major profitable and underperforming areas.

---

# Page 2 — Profitability & Loss Analysis

The second page focuses specifically on identifying profitability problems.

### Key visuals include:

- Total Loss
- Loss Transactions
- Average Discount
- Profit by Sub-category
- Profit by Region
- Discount vs Profit
- Top Loss-Making Products
- High-Sales Loss-Making Transactions

### Purpose

This page helps identify:

- Where losses are occurring
- Which sub-categories are responsible
- Which regions are contributing to losses
- Which products are generating significant losses
- Whether high discounts are associated with losses
- Which individual transactions require further investigation

---

# 💡 Key Business Insights

The major findings from the analysis were:

### 1. Technology was the strongest category

Technology generated the highest overall profit among the three major categories.

### 2. Furniture had weak profitability

Furniture had significantly lower profitability compared with Technology and Office Supplies.

### 3. Some sub-categories caused significant losses

Tables, Machines and Binders were among the major loss-making sub-categories.

### 4. High sales do not guarantee high profit

Several transactions generated high sales but still resulted in negative profit.

### 5. Discounts are an important profitability factor

High-sales loss-making transactions had an average discount of approximately **34.23%**, compared with approximately **15.62% overall**.

### 6. Regional profitability varies

Different regions and states showed substantial differences in profitability and losses.

### 7. Product-level analysis is important

Some individual products generated significant losses and therefore reduced the profitability of their respective categories.

---

# 💼 Business Recommendations

Based on the analysis, the following recommendations can be considered:

### 1. Review discount strategies

Avoid excessive discounts on products with already low profit margins.

### 2. Investigate loss-making sub-categories

Products in sub-categories such as Tables, Machines and Binders should be investigated for:

- Pricing
- Procurement costs
- Discount levels
- Operating costs
- Product margins

### 3. Monitor high-sales low-profit transactions

High revenue should not be treated as the only measure of success. Profitability should also be considered.

### 4. Analyze regional differences

Regional pricing, customer behavior, discounting and product mix should be investigated to understand why profitability differs across regions.

### 5. Focus on profitable product categories

The business can evaluate opportunities to increase the contribution of stronger-performing categories while improving weak-performing areas.

---

# 📁 Project Structure

```text
Superstore-Sales-Profitability-Analysis/
│
├── README.md
│
├── Superstore_EDA.ipynb
│
├── Superstore_Analysis.pbix
│
├── Sample-Superstore.csv
│
└── Dashboard/
    ├── Page1_Overview.png
    └── Page2_Profitability.png
