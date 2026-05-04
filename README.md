# Financial Performance Dashboard 2023

## 1. Project Context

This project analyzes the 2023 financial performance of a sports and wellness-related retail company. The company operates across three main business lines: Sports equipment, Sportswear, and Nutrition and Food Supplements.

The purpose of this project is to go beyond basic financial reporting and use Power BI to understand how revenue is converted into profit, which business lines contribute most effectively, and which cost categories create the greatest pressure on profitability.

## 2. Dataset

The dataset contains monthly revenue and expense records for the company in 2023. Each row represents a financial record by month, business line, income or expense type, income/expense group, and expense subgroup.

The dataset is used to calculate financial metrics such as total revenue, total expense, net profit, profit margin, expense ratio, COGS, OPEX, and EBIT.

### Data Dictionary

| Column | Description |
|---|---|
| Year | Year of revenue or expense |
| Month - name | Month of revenue or expense |
| Month - sequence | Month of revenue or expense, expressed as a number |
| Date | Date of revenue or expense, expressed as the last day of the month |
| Business Line | Business line generating revenue or expense, including Sports equipment, Sportswear, and Nutrition and Food Supplements |
| Amount, $ | Revenue or expense amount in USD |
| Expense subgroup | Additional subgroup categorizing expenses associated with OPEX and COGS |
| Income / Expense Group | Subcategory of revenue or expense. Revenue subcategories include Sales, Consulting and Professional Services, and Other Income. Expense subcategories include OPEX, COGS, and Interest and Tax |
| Income or expense | Column indicating whether the associated amount is revenue or expense |

## 3. Project Objectives

The objective of this project is to build a Power BI dashboard that supports financial and strategic decision-making.

The dashboard is designed to answer the following business questions:

1. Is the company financially healthy overall?
2. How did revenue, expenses, and profit change over time?
3. Which business lines should be prioritized, maintained, optimized, or reviewed?
4. Which cost categories create the most pressure on profitability?
5. Where should cost optimization efforts be focused?

## 4. Report Audience

This dashboard is designed for management, finance teams, business line managers, and operations or strategy teams.

- Management teams can use the dashboard to evaluate overall financial health and make resource allocation decisions.
- Finance teams can use it to monitor revenue, expenses, COGS, OPEX, EBIT, profit margin, and expense ratio.
- Business line managers can use it to compare the performance of each business line.
- Operations and strategy teams can use it to identify cost drivers and optimization opportunities.

## 5. Tools Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Financial Analysis
- Data Storytelling

## 6. Key Metrics

The dashboard includes the following key metrics:

- Total Revenue
- Total Expense
- Net Profit
- Profit Margin
- Expense Ratio
- COGS
- OPEX
- EBIT
- Revenue by Business Line
- Expense by Group
- Cost Optimization Priority

## 7. Dashboard Pages

### Page 1: Overview

This page provides a high-level summary of the company’s financial performance in 2023. It gives a quick view of revenue, expenses, net profit, profit margin, and expense ratio, while also showing how revenue is converted into net profit after major cost layers.
![Overview](images/overview.PNG)

### Page 2: Financial Performance Analysis

This page analyzes how revenue, expenses, net profit, COGS, and OPEX changed over time. It helps evaluate whether revenue growth was translated into profit improvement.
![Financial Performance Analysis](images/financial-performance-analysis.PNG)

### Page 3: Business Line Performance

This page compares Sports equipment, Sportswear, and Nutrition and Food Supplements in terms of revenue, expenses, net profit, and profit margin. It identifies which business lines drive revenue scale, which ones generate stronger profitability, and which ones require review.
![Business Line Performance](images/business-line-performance.PNG)

### Page 4: Cost and Category Analysis

This page analyzes the company’s expense structure and identifies major cost drivers. It also classifies cost categories based on whether they can be optimized, reviewed carefully, or are difficult to reduce.
![Cost and Category Analysis](images/cost-category-analysis.PNG)

## 8. Key Insights

### 8.1 Overview

In 2023, the business remained profitable, generating 17.56M in revenue and 4.31M in net profit, with an overall profit margin of 24.57%. However, the expense ratio of 75.43% indicates that a large share of revenue was consumed by costs. The profit bridge shows that COGS and OPEX are the main cost layers reducing profitability, while business line analysis reveals that Sportswear contributes the strongest margin, whereas Nutrition and Food Supplements shows a negative margin. Therefore, the key financial decision is not only to grow revenue, but also to prioritize profitable business lines and review major cost drivers such as labor, payroll, equipment, and marketing.

### 8.2 Financial Performance Analysis

The company maintained positive revenue throughout the year, but profitability fluctuated significantly across months. Net profit did not always move in line with revenue growth, suggesting that revenue growth alone was not enough to secure stronger financial performance. The trend analysis shows that COGS and OPEX played a key role in shaping monthly net profit, with COGS being the larger cost layer. Business line revenue was mainly driven by Sports equipment, while Nutrition and Food Supplements contributed a smaller share. Overall, the P&L breakdown shows that although the company generated 17.56M in revenue and 5.24M EBIT, cost control remains the main priority, especially in COGS and OPEX, to improve profitability.

**Key message:** The business is generating revenue, but profit improvement depends on whether revenue can grow faster than COGS and OPEX.

### 8.3 Business Line Performance

The Business Line Performance page shows that total revenue reached 17.56M, leaving 4.31M in net profit after COGS, OPEX, interest, and tax. However, profitability is uneven across business lines. Sports equipment generated the highest revenue at 8.9M, but its high expense level of 6.6M reduced net profit to 2.3M, with a profit margin of 25.7%. This suggests that Sports equipment is important for revenue scale but should be optimized to improve cost efficiency.

Sportswear generated lower revenue at 6.8M, but with only 4.1M in expenses, it delivered the highest net profit of 2.7M and the strongest profit margin at 40.2%. This indicates that Sportswear converts revenue into profit more effectively and should be prioritized for further investment or growth.

In contrast, Nutrition and Food Supplements generated only 1.8M in revenue but incurred 2.6M in expenses, resulting in a negative net profit of -0.7M and a negative margin of -38.7%. This business line should be reviewed before allocating additional resources.

**Key message:** Sportswear is the most profitable business line, Sports equipment drives revenue scale, and Nutrition and Food Supplements requires review due to negative profitability.

### 8.4 Cost and Category Analysis

The Cost and Category Analysis page shows that total expenses reached 13.25M in 2023, accounting for 75.43% of total revenue. COGS was the largest expense group at 6.71M, representing 50.67% of total expenses, followed by OPEX at 5.60M or 42.31%. Interest and tax accounted for only 0.93M, suggesting that the main cost pressure came from production-related costs and operating expenses rather than financing or tax-related items.

Over time, COGS remained higher than OPEX in most months, especially around May and June, while OPEX stayed relatively stable but still represented a significant cost layer. The largest cost drivers were Labor, Payroll, and Equipment, indicating that people and operating capacity were the main areas behind total expenses.

The cost ratio trend shows that both COGS and OPEX ratios increased from Q1 to Q3 before declining in Q4. From the cost control detail, variable costs such as Marketing, Materials, Packaging, and Shipping can be optimized first, while semi-fixed and fixed costs such as Labor, Payroll, and Equipment should be reviewed carefully.

**Key message:** Cost pressure is mainly driven by COGS and OPEX, especially labor, payroll, and equipment. The priority should be to optimize variable costs first and carefully review semi-fixed and fixed costs before making reduction decisions.

## 9. Recommendations

Based on the analysis, the company should focus on improving profitability through selective growth and cost optimization.

Recommended actions:

- Prioritize Sportswear because it has the strongest profit margin and highest net profit.
- Maintain and optimize Sports equipment because it drives the largest revenue but also carries high expenses.
- Review Nutrition and Food Supplements because it currently generates negative profit.
- Optimize variable costs first, especially marketing, materials, packaging, and shipping.
- Review labor, payroll, and equipment carefully before making cost reduction decisions.
- Focus on improving how revenue is converted into profit, not only increasing revenue volume.

## 10. Strategic Summary

The recommended business direction is:

| Business Line | Decision |
|---|---|
| Sportswear | Prioritize |
| Sports equipment | Maintain / Optimize |
| Nutrition and Food Supplements | Review |

Overall, the company should grow the most profitable business line, protect the main revenue driver, and review the loss-making segment while optimizing costs selectively.

## 11. Project Files

```text
financial-performance-dashboard-powerbi/
│
├── README.md
├── dashboard/
│   └── Financial_Performance_Dashboard.pbix
├── data/
│   └── Financial_analysis_dataset.xlsx
└── images/
   ├── overview.PNG
   ├── financial-performance-analysis.PNG
   ├── business-line-performance.PNG
   └── cost-category-analysis.PNG
