# Workforce Insight Navigator

### Overview

Workforce Insight Navigator is a Power BI based HR analytics solution designed to analyze workforce demographics, attrition patterns, and employee wellness indicators. The dashboard converts structured HR data into analytical insights that support workforce planning, retention strategy, and employee experience optimization.

The project emphasizes data preprocessing, metric-driven analysis, and interactive visualization to enable evidence-based HR decision-making.

### Project Objective

The objective was to build a scalable and interactive HR dashboard that provides insights into:

Workforce composition and demographic distribution

Attrition rates and key turnover drivers

Employee wellness, satisfaction, and engagement indicators

The solution is intended to function as a decision-support system for HR leaders and business managers.

### Data Pipeline & Methodology
1. Data Preprocessing (Power Query)

   Removed redundant and non-informative columns

   Handled missing values and eliminated duplicate records

   Standardized column naming conventions and data types

   Applied transformations in Power Query Editor to ensure data consistency

   Produced a clean, analysis-ready data model

2. Data Model & Metrics

   Defined calculated measures for:

   Attrition rate

   Active vs exited employees

   Average tenure

   Average monthly income and hourly rate

   Used DAX measures to support KPI cards and cross-dashboard filtering

   Enabled relationships for multi-dimensional slicing (department, role, job level, performance, demographics)

### Dashboard Architecture

The solution consists of four analytical dashboards:

1. Demographics Dashboard

   Employee distribution by age group, gender, marital status, and commute distance

   Attrition analysis segmented by demographic attributes

   High-level workforce diversity overview

2. Turnover Analysis I

   Attrition breakdown by department, job role, business travel, and tenure

   Identification of high-risk functions and roles

   Supports workforce planning and retention prioritization

3. Turnover Analysis II

   Attrition analysis by job level, overtime, income bands, and performance ratings

   Evaluation of managerial and performance-linked attrition

   Highlights compensation and workload-related risks

4. Employee Wellness Dashboard

   Analysis of work-life balance, job satisfaction, relationship satisfaction, and environment satisfaction

   Correlation between satisfaction metrics and attrition

   Identification of non-compensation drivers of employee exit

### Key Analytical Insights
Workforce & Demographics:

Overall attrition rate: 16.12%, reducing active employees from 1,470 to 1,233

Highest attrition observed in the 31–40 age group

Life Sciences education background shows the highest attrition

Gender-wise attrition split: 63% male, 37% female

Married employees demonstrate lower attrition compared to single employees

Turnover Drivers:

Average employee tenure: 11.28 years

Sales Executives and R&D exhibit the highest attrition, with R&D at 56%

Higher overtime exposure correlates with increased attrition, particularly among men

Performance & Compensation:

Managers experience the highest attrition, followed by Sales Directors

Employees with lower performance ratings contribute to 84% of total attrition

Higher hourly rates do not necessarily reduce attrition, indicating non-monetary exit drivers

Wellness Indicators:

Average monthly income: $6.5K

Average hourly rate: $65.89

Employees reporting good work-life balance still account for 54% attrition, suggesting external mobility or market-driven exits

Men show moderate job involvement compared to women

### Conclusion

The Workforce Insight Navigator demonstrates how HR data can be modeled, analyzed, and visualized using Power BI, DAX, and Power Query to uncover meaningful workforce patterns. The dashboard enables organizations to move beyond descriptive reporting toward diagnostic and strategic HR analytics, supporting data-driven retention, engagement, and workforce optimization initiatives.

### Tech Stack & Skills:
Power BI | DAX | Power Query | HR Analytics | Data Modeling | Data Visualization | KPI Design
