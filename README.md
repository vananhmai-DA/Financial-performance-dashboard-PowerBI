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

![Overview](images/Overview.png)

**Key insight:**  
The company was profitable overall in 2023, with 17.56M in revenue and 4.31M in net profit. However, the expense ratio of 75.43% shows that a large share of revenue was consumed by costs. This means the key question is not only whether the company can generate revenue, but which parts of the business convert revenue into profit efficiently and which parts create cost pressure.

---

### Page 2: Financial Performance Analysis

This page analyzes how revenue, expenses, net profit, COGS, and OPEX changed over time. It helps evaluate whether revenue growth was translated into profit improvement.

![Financial Performance Analysis](images/Financial%20trends.png)

**Key insight:**  
Revenue remained positive throughout the year, but profit performance fluctuated across months. This suggests that weaker profit months were not caused by a lack of revenue alone. Instead, the gap between revenue and profit points to cost pressure as a key factor, especially when COGS and OPEX remained high. Therefore, the next step is to identify whether the profit pressure came from specific business lines or cost categories.

---

### Page 3: Business Line Performance

This page compares Sports equipment, Sportswear, and Nutrition and Food Supplements in terms of revenue, expenses, net profit, and profit margin. It identifies which business lines drive revenue scale, which ones generate stronger profitability, and which ones require review.

![Business Line Performance](images/Business%20lines.png)

**Key insight:**  
The business line analysis identifies Nutrition and Food Supplements as the main loss-making segment. It generated only 1.8M in revenue but incurred 2.6M in expenses, resulting in -0.7M net profit and a negative margin of -38.7%. Compared with Sports equipment and Sportswear, this segment has both the lowest revenue and the weakest cost efficiency. This suggests that the loss is caused by both weak revenue contribution and expenses that are too high relative to the revenue generated.

---

### Page 4: Cost and Category Analysis

This page analyzes the company’s expense structure and identifies major cost drivers. It also classifies cost categories based on whether they can be optimized, reviewed carefully, or are difficult to reduce.

![Cost and Category Analysis](images/Cost%20analysis.png)

**Key insight:**  
After identifying cost pressure as a key issue, the cost analysis shows that COGS and OPEX are the main expense groups. COGS reached 6.71M, while OPEX reached 5.60M. The largest cost drivers are Labor, Payroll, and Equipment, which are related to people and operating capacity. Therefore, the company should not cut costs blindly. Instead, it should optimize flexible costs such as Marketing, Materials, Packaging, and Shipping first, and carefully review Labor, Payroll, and Equipment based on productivity, utilization, and contribution to revenue.

## 8. Business Findings and Recommendations

### 8.1 Conclusion

The company remained profitable in 2023, generating 17.56M in revenue and 4.31M in net profit. However, the expense ratio was high at 75.43%, which means a large share of revenue was consumed by costs.

The main issue is not simply revenue generation, because the company maintained positive revenue throughout the year. The deeper issue is profit conversion. Revenue did not always translate into stronger profit due to high cost pressure from COGS and OPEX.

At the business line level, Sportswear showed the strongest profitability, while Sports equipment generated the largest revenue but carried higher expenses. Nutrition and Food Supplements was the only loss-making business line, with expenses higher than revenue.

At the cost level, COGS and OPEX were the main cost layers affecting profitability. Labor, Payroll, and Equipment were the largest cost drivers, suggesting that the company should review cost efficiency carefully before making reduction decisions.

### 8.2 Recommendations

Based on the analysis, the company should focus on improving profit conversion rather than only increasing revenue.

- Prioritize Sportswear because it has the strongest profit margin and converts revenue into profit most effectively.
- Maintain and optimize Sports equipment because it is the largest revenue driver, but its high expense level reduces profitability.
- Review Nutrition and Food Supplements before further investment because this business line generated negative profit.
- Optimize variable costs first, especially Marketing, Materials, Packaging, and Shipping, because these costs are more flexible.
- Review Labor, Payroll, and Equipment carefully before cutting costs, because these costs may directly support operations and revenue generation.

### 8.3 Strategic Summary

The recommended strategy is to grow profitable revenue, protect the main revenue driver, and review the loss-making business line.

| Business Line | Decision | Reason |
|---|---|---|
| Sportswear | Prioritize | Highest profit margin and strongest profit conversion |
| Sports equipment | Maintain / Optimize | Largest revenue driver but high expense level |
| Nutrition and Food Supplements | Review | Negative profit and expenses higher than revenue |

Overall, the company should not cut costs blindly. Instead, it should optimize costs selectively by focusing on flexible cost categories first, while carefully reviewing major cost drivers that support business operations.

**Strategic direction:**  
Improve profitability by prioritizing high-margin business lines, optimizing high-cost revenue drivers, and reviewing loss-making activities before further investment.
