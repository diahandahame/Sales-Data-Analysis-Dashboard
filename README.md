# Superstore Sales Performance Analysis
## Excel | Data Analysis | Business Intelligence

---
## Project Overview
This project delivers a comprehensive sales performance analysis of a fictional US retail company, the Superstore, covering four years of transactional data (2014–2017) across three product categories, four geographic regions, and over 9,900 order lines.

Built entirely in Microsoft Excel, the project follows a full analytical pipeline from data cleaning and feature engineering to structured pivot analysis, dashboard design, and business recommendations.

The objective is to move beyond descriptive reporting and produce actionable insights for decision-makers, identifying profit leakage, inefficient discounting practices, and untapped seasonal opportunities.

---
## Dataset
Source: [Superstore Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/himanshuuike/superstore-sales-dataset)

The analysis is based on the Sample Superstore dataset:

- 9,994 transaction lines  
- 5,009 unique orders  
- Coverage across 49 U.S. states and 4 regions  
- Period: January 2014 to December 2017
- 
A key analytical consideration is that the dataset contains approximately two transaction lines per order. Analysing the data at line level would therefore overstate order volume.  
To ensure accuracy and business relevance, all KPIs are calculated at the unique order level.

---
## Tools and Skills Demonstrated
- Microsoft Excel  
- Structured tables and named ranges  
- Dynamic formulas: UNIQUE, COUNTA, IFERROR, NBVAL  
- Pivot tables and KPI design  
- Dashboard structuring  
- Business insight communication  

---
## Methodology

### Data Cleaning
Date formats were standardised, inconsistent data types corrected, and a reliable unique order count established using the UNIQUE function.

### Feature Engineering
Five derived variables were created:
- Profit Margin (Profit / Sales with IFERROR)  
- Month  
- Season (Winter, Spring, Summer, Autumn)  
- Discount Group (0%, 0–20%, 20–40%, 40%+)  

### Analysis
Six pivot tables were built:
- Regional performance  
- Profit by sub-category  
- Discount impact  
- State-level profitability  
- Monthly trends  
- Category comparison  

### Dashboard
An executive dashboard was created with eight key performance indicators and a structured layout.

---
## Key Findings

### Regional Profitability
- Total revenue: $2,295,274  
- Total profit: $285,988  
- Overall margin: 12.5%  

- West: $725,458 sales, 14.9% margin  
- East: $678,664 sales, 13.5% margin  
- South: $391,021 sales, 11.9% margin  
- Central: $500,130 sales, 7.9% margin  

The Central region significantly underperforms relative to its revenue level, suggesting pricing or discounting inefficiencies.

---
### Category Performance
- Technology: $834,227 sales, $145,046 profit, 17.4% margin  
- Office Supplies: $719,047 sales, $122,491 profit, 17.0% margin  
- Furniture: $742,000 sales, $18,451 profit, 2.5% margin  

Furniture shows structurally low profitability. At sub-category level, Tables, Bookcases, and Supplies are loss-making.

---
### Discount Impact
Discounting has a direct negative impact on profitability:

- 0% discount generates high margins (~30%)  
- Around 30% discount, profit becomes negative  
- At 70% discount, losses exceed revenue contribution  

#### By discount group:
- 0–20%: +$100,479 profit  
- 20–40%: −$35,817  
- 40%+: −$99,559  

High discounts do not generate sufficient volume to offset margin loss.

---
### Monthly and Seasonal Trends
- Best month: September (20.1% margin)  
- Strong months: May, March  
- Weak months: August (4.6%), July (8.9%), April (9.2%)  

The gap between August and September highlights a missed seasonal opportunity.

---
### State-Level Profitability

#### Top contributors:
- California: $76,381  
- New York: $74,039  

#### Major loss-making states:
- Texas: −$25,729  
- Ohio: −$16,971  
- Pennsylvania: −$15,582  

These states represent the most immediate recovery opportunity.

---
## Recommendations

### Cap Discounts at 20%
All discount levels above 20% generate net losses. A strict ceiling would protect profitability.

### Apply Category-Specific Discount Limits
- Furniture: 10% maximum  
- Technology: 15% maximum  
- Office Supplies: 20% maximum  

### Replace Deep Discounts with Value-Based Offers
Bundles, free shipping, and extended warranties preserve margin while maintaining perceived value.

### Audit the Central Region
A detailed analysis of discount practices and pricing strategy is required.

### Invest in July and August
Targeted campaigns should focus on demand stimulation without aggressive discounting.

### Leverage September Performance
Increase upsell and cross-sell efforts during the strongest month.

### Focus on Loss-Making States
Prioritise Texas, Ohio, and Pennsylvania for corrective actions.

---
## Summary
This project demonstrates a full analytical workflow from raw data to business recommendations.

The central insight is that the business does not have a revenue problem but a discount policy problem.

With $2.3 million in sales, the revenue base is strong. However, excessive discounting and structurally low margins in Furniture significantly reduce profitability.

Targeted pricing adjustments and seasonal strategies could recover between $60,000 and $80,000 in profit annually without increasing customer acquisition.
