# 📊 Superstore Sales Performance Analysis
Excel | Data Analysis | Business Intelligence

---

## 📌 Project Overview

This project delivers a comprehensive sales performance analysis of a
fictional US retail company, the Superstore, covering four years of
transactional data (2014-2017) across three product categories, four
geographic regions, and over 9,900 order lines.

Built entirely in **Microsoft Excel**, the project follows a full
analytical pipeline from data cleaning and feature engineering to
structured pivot analysis, dashboard design, and business recommendations.

The objective is to move beyond descriptive reporting and produce
**actionable insights for decision-makers**, identifying profit leakage,
inefficient discounting practices, and untapped seasonal opportunities.

---

## 🗂️ Dataset

**Source:** [Superstore Sales Dataset - Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

- 9,994 transaction lines
- 5,009 unique orders
- Coverage across 49 U.S. states and 4 regions
- Period: January 2014 to December 2017

> A key analytical consideration is that the dataset contains approximately
> two transaction lines per order. Analysing the data at line level would
> overstate order volume. All KPIs are therefore calculated at the
> unique order level.

---

## 🛠️ Tools and Skills Demonstrated

| Skill | Detail |
|---|---|
| **Structured tables** | Named ranges and organized data model |
| **Dynamic formulas** | UNIQUE, COUNTA, IFERROR, NBVAL |
| **Feature engineering** | Derived variables for deeper analysis |
| **Pivot tables** | 6 pivot tables across key business dimensions |
| **KPI design** | 8 executive-level indicators |
| **Dashboard** | Interactive layout for decision-makers |
| **Business communication** | Actionable recommendations per finding |

---

## 🔬 Methodology

### Data Cleaning
Date formats standardised, inconsistent data types corrected, and a
reliable unique order count established using the UNIQUE function.

### Feature Engineering
Five derived variables were created:
- Profit Margin (Profit / Sales with IFERROR)
- Month
- Season (Winter, Spring, Summer, Autumn)
- Discount Group (0%, 0-20%, 20-40%, 40%+)

### Analysis
Six pivot tables were built across the following dimensions:
- Regional performance
- Profit by sub-category
- Discount impact
- State-level profitability
- Monthly trends
- Category comparison

---

## 📈 Dashboard

![Dashboard](Dashboard.png)

---

## 🔍 Key Findings

### 🌍 Regional Profitability

| Region | Sales | Margin |
|---|---|---|
| West | $725,458 | 14.9% |
| East | $678,664 | 13.5% |
| South | $391,021 | 11.9% |
| Central | $500,130 | 7.9% |

**Total revenue:** $2,295,274 - **Total profit:** $285,988 - **Overall margin:** 12.5%

> The Central region significantly underperforms relative to its revenue
> level, suggesting pricing or discounting inefficiencies.

---

### 📦 Category Performance

| Category | Sales | Profit | Margin |
|---|---|---|---|
| Technology | $834,227 | $145,046 | 17.4% |
| Office Supplies | $719,047 | $122,491 | 17.0% |
| Furniture | $742,000 | $18,451 | 2.5% |

> Furniture shows structurally low profitability. Tables, Bookcases,
> and Supplies are loss-making at sub-category level.

---

### 💸 Discount Impact

| Discount Group | Profit Impact |
|---|---|
| 0-20% | +$100,479 |
| 20-40% | -$35,817 |
| 40%+ | -$99,559 |

> High discounts do not generate sufficient volume to offset margin loss.
> Around 30% discount, profit becomes negative.

---

### 📅 Monthly and Seasonal Trends

- **Best month:** September (20.1% margin)
- **Strong months:** May, March
- **Weak months:** August (4.6%), July (8.9%), April (9.2%)

> The gap between August and September highlights a missed seasonal
> opportunity.

---

### 🗺️ State-Level Profitability

**Top contributors:**
- California: $76,381
- New York: $74,039

**Major loss-making states:**
- Texas: -$25,729
- Ohio: -$16,971
- Pennsylvania: -$15,582

---

## 💡 Recommendations

| Priority | Action |
|---|---|
| 1 | Cap all discounts at 20% |
| 2 | Apply category-specific limits (Furniture 10%, Technology 15%, Office Supplies 20%) |
| 3 | Replace deep discounts with value-based offers (bundles, free shipping) |
| 4 | Audit Central region discount practices |
| 5 | Invest in July and August demand stimulation |
| 6 | Leverage September with upsell and cross-sell efforts |
| 7 | Focus recovery actions on Texas, Ohio, and Pennsylvania |

---

## 📝 Summary

This project demonstrates a full analytical workflow from raw data to
business recommendations.

> The central insight is that **the business does not have a revenue
> problem but a discount policy problem.**

With $2.3 million in sales, the revenue base is strong. However,
excessive discounting and structurally low margins in Furniture
significantly reduce profitability.

Targeted pricing adjustments and seasonal strategies could recover
between **$60,000 and $80,000 in profit annually** without increasing
customer acquisition.

---

## 👤 Author

**Handahamé DIA** - Quantitative Economist | Sales and Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Handahamé_DIA-blue?logo=linkedin)](https://www.linkedin.com/in/handahame-dia/)
[![GitHub](https://img.shields.io/badge/GitHub-diahandahame-black?logo=github)](https://github.com/diahandahame)
