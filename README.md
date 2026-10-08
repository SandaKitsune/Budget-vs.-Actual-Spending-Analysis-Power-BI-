# Budget-vs.-Actual-Spending-Analysis-Power-BI-
An interactive Power BI dashboard that compares planned budget with actual spending to identify budget variances, overspending patterns, and the main cost drivers across departments, regions, and spending categories.

<img width="464" height="257" alt="budget actual visual" src="https://github.com/user-attachments/assets/24da084d-6c60-4627-8703-b4e3b4d48f71" />

**Business Questions**

•	Which departments and regions are exceeding their allocated budgets?

•	How does actual spending compare with budget over time (year, quarter, month)?

•	Which spending categories drive the largest variances?

**Data**

•	Source: [Budget vs Actual Financial Dataset / Kaggle public sample] (https://www.kaggle.com/datasets/kennathalexanderroy/budget-vs-actual-financial-dataset)

•	Period: 2021–2023

•	Fields: budget and actual amounts, departments, regions, spending categories, payment methods, dates


**Tools**

Power BI Desktop · Power Query · DAX

**Dashboard Structure**
|Page|Content|
|------|---------|
|**Overview**|Purpose, dataset description, and analysis objectives|
|**Budget performance**|KPI cards (actual vs. budget, excess, excess %, difference %), year/category /                                               region slicers, budget vs. actual trend by year, quarter and                                                                 month, comparison by region, and matrices of variance by department and                                                      region and excess by department and category|
|**Analysis**|Key trends and findings by year, with an overall insight|


**Key Findings**

Actual spending exceeded budget in all three years: approximately $31M in 2021, $36M in 2022, and $28M in 2023.

•	2023: the Central region had the largest variance (about $6M), with IT as the main contributor (about $2M), largely driven by salary costs.

•	2022: the highest overspend of the period; the Southern region led (about $9M), and HR had the highest departmental variance.

•	2021: the Eastern region had the highest regional variance (about $9M), and Finance recorded the largest departmental variance.

Overall: salary-related costs are one of the most consistent drivers of variance, and the departments behind overspending differ by region and year.

**How to Open**


Download report/budget_actual.pbix and open it with Power BI Desktop (Windows).

