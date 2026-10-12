# Loan Recovery & Outstanding Analysis | Excel Dashboard

## Project Overview

This project analyzes loan recovery operations using Microsoft Excel. It focuses on outstanding loan amounts, recovered amounts, recovery methods, delinquency buckets, recovery agencies, regional performance, and monthly trends.

The goal is to understand how recovery outcomes vary across different business dimensions and identify areas where further investigation could improve recovery operations.

## Business Problem

Loan recovery teams need to monitor more than the total amount recovered. They also need to understand how much remains outstanding, which cases are still open, how recovery performance differs by loan type and region, and how recovery costs affect operational decisions.

This project explores the following questions:

* How much outstanding and recovered value is recorded?
* What proportion of outstanding value has been recovered?
* Which loan types contribute most to outstanding amounts?
* How do recovery methods compare?
* How does recovery performance vary by region and agency?
* How are cases distributed across delinquency buckets?
* How do outstanding amounts, recoveries, and legal costs change month by month?

## Dataset Overview

* **Records:** 5,562 loan recovery cases
* **Reporting period:** January–December 2024
* **Columns:** 16
* **Tool:** Microsoft Excel

Key fields include Case ID, Case Date, Recovery Agency, Region, Loan Type, Delinquency Bucket, Recovery Method, Case Status, Outstanding Amount USD, Recovered Amount USD, Days Open, Legal Cost USD, Month, and Year.

## Tools & Techniques

* Microsoft Excel
* PivotTables and PivotCharts
* KPI calculations
* Data aggregation and comparison
* Monthly trend analysis
* Recovery rate analysis
* Delinquency and recovery method analysis
* Dashboard-based reporting

## Dashboard Preview



## Key Performance Indicators

| KPI                       |            Result |
| ------------------------- | ----------------: |
| Total Cases               |             5,562 |
| Total Outstanding Amount  | $1,400,728,236.54 |
| Total Recovered Amount    |   $430,235,827.44 |
| Amount Recovery Rate      |            30.72% |
| Total Legal Costs         |    $13,950,665.02 |
| Open Cases                |             1,132 |
| Written-Off Cases         |             1,095 |
| Partially Recovered Cases |             1,086 |
| Average Days Open         |            186.89 |

### KPI Definitions

**Amount Recovery Rate**

Total Recovered Amount / Total Outstanding Amount × 100

**Average Days Open**

Sum of recorded Days Open / Number of Cases

**Legal Cost**

Sum of recorded Legal Cost USD values.

The recovery rate measures recovered value relative to outstanding value. It is not the percentage of cases fully recovered.

## Chart-by-Chart Analysis

### Dashboard 1: Overview
<img width="1747" height="758" alt="Screenshot 2026-10-12 083854" src="https://github.com/user-attachments/assets/0e276162-2865-4c49-94e6-862733755a97" />

#### 1. Total Cases

**Purpose:** To show the total number of cases included in the dataset.

**Interpretation:** The dataset contains 5,562 cases recorded during 2024.

**Business value:** This KPI provides the overall scale of the recovery portfolio.

**Recommended action:** Monitor case volume over time and compare it with recovery outcomes and operational capacity.

#### 2. Total Outstanding Amount

**Purpose:** To measure the total outstanding amount recorded across the cases.

**Interpretation:** The dataset records approximately $1.40 billion in outstanding amounts.

**Business value:** This KPI provides a high-level view of the financial exposure represented in the dataset.

**Recommended action:** Break the amount down by loan type, delinquency bucket, region, and case status to identify where the largest balances are concentrated.

#### 3. Total Recovered Amount

**Purpose:** To show the total value recorded as recovered.

**Interpretation:** Approximately $430.24 million is recorded as recovered.

**Business value:** This measure indicates the scale of recorded recovery activity.

**Recommended action:** Compare recovered amounts with outstanding amounts and recovery costs to evaluate results in context.

#### 4. Amount Recovery Rate

**Purpose:** To measure recovered value as a proportion of outstanding value.

**Interpretation:** The recorded amount recovery rate is approximately 30.72%.

**Business value:** This indicator allows recovery performance to be tracked over time and compared across business segments.

**Recommended action:** Track the rate by month, loan type, region, and recovery method. Confirm the business definition of outstanding amount before treating this metric as a formal collection-efficiency measure.

### Dashboard 2: Loan Analysis
<img width="1745" height="756" alt="Screenshot 2026-10-12 083923" src="https://github.com/user-attachments/assets/f1e1e948-52a8-444f-8d53-51382584c98f" />

#### 5. Outstanding Amount by Loan Type

**Purpose:** To compare the outstanding amounts associated with different loan types.

**Interpretation:** The chart compares Auto, Home, Personal, and SME loans.

**Business value:** It shows which loan categories account for larger outstanding balances.

**Recommended action:** Compare outstanding amounts with recovered amounts, delinquency distribution, and case counts before prioritizing a loan category.

#### 6. Recovered Amount by Loan Type

**Purpose:** To compare recovered values across loan categories.

**Interpretation:** Larger values indicate higher recorded recovery amounts.

**Business value:** This helps show where recovered value is concentrated.

**Recommended action:** Compare each loan type's recovery rate rather than relying only on absolute recovered amounts.

#### 7. Case Distribution by Loan Type

**Purpose:** To understand how cases are distributed across loan categories.

**Interpretation:** Each category's value represents its share or count of the case portfolio, depending on the chart's measure.

**Business value:** Case volume provides context for interpreting recovery amounts.

**Recommended action:** Use case counts and financial amounts together to avoid confusing a high-volume category with a high-performing category.

#### 8. Loan Recovery Performance Comparison

**Purpose:** To compare recovery outcomes across loan types.

**Interpretation:** Compare recovered and outstanding amounts using the measures displayed in the chart.

**Business value:** The comparison helps identify categories for deeper investigation.

**Recommended action:** Include recovery rate and average days open in the comparison before recommending operational changes.

### Dashboard 3: Recovery Method Analysis
<img width="1720" height="722" alt="Screenshot 2026-10-12 083951" src="https://github.com/user-attachments/assets/cf142197-dd5e-43a8-aee7-e9eaef6ede66" />

#### 9. Outstanding Amount by Recovery Method

**Purpose:** To compare outstanding balances associated with different recovery methods.

**Interpretation:** The chart compares Call Center, Field Visit, Legal Notice, Repossession, and Settlement.

**Business value:** It helps identify where outstanding balances are concentrated across recovery approaches.

**Recommended action:** Compare the results with recovered amounts, legal costs, and delinquency mix. The outstanding amount associated with a method does not prove that the method caused better or worse results.

#### 10. Recovered Amount by Recovery Method

**Purpose:** To compare recorded recovered amounts across methods.

**Interpretation:** Higher values indicate more recovered value associated with a particular method.

**Business value:** This supports a comparison of the financial outcomes recorded for different recovery approaches.

**Recommended action:** Evaluate recovery rate, cost per recovery, and case complexity before deciding which method to expand.

#### 11. Recovery Rate by Recovery Method

**Purpose:** To compare the proportion of outstanding value recovered across recovery methods.

**Interpretation:** A higher percentage indicates a larger recovered amount relative to the outstanding amount for that method.

**Business value:** Rate-based comparisons provide additional context beyond raw amounts.

**Recommended action:** Review sample sizes, delinquency mix, and costs alongside the rate. A higher observed rate does not by itself establish that the method is more effective.

### Dashboard 4: Total Outstanding Analysis
<img width="1745" height="757" alt="Screenshot 2026-10-12 084023" src="https://github.com/user-attachments/assets/1c08fac9-96a8-437a-9ff7-71e03281c574" />

#### 12. Outstanding Amount by Region

**Purpose:** To compare outstanding balances across regions.

**Interpretation:** The chart compares Central Region, East Zone, North Zone, South Zone, and West Zone.

**Business value:** It shows how outstanding amounts are distributed geographically.

**Recommended action:** Compare the distribution with regional case counts and recovery rates to identify areas requiring further analysis.

#### 13. Recovery Rate by Region

**Purpose:** To compare recovered value as a proportion of outstanding value across regions.

**Interpretation:** Regional rates show differences in recorded recovery performance.

**Business value:** This helps identify regional variation that may warrant investigation.

**Recommended action:** Examine delinquency mix, recovery methods, and legal costs before attributing differences to regional operations.

#### 14. Legal Costs by Loan Type

**Purpose:** To compare recorded legal costs across loan categories.

**Interpretation:** Higher values indicate greater total legal expenditure associated with a loan type.

**Business value:** This shows where legal costs are concentrated.

**Recommended action:** Compare legal costs with recovered amounts and case counts. Total cost alone does not indicate whether spending is excessive or justified.

### Dashboard 5: Month Analysis
<img width="1680" height="722" alt="Screenshot 2026-10-12 084045" src="https://github.com/user-attachments/assets/c42e9b0c-bb0f-4633-aa23-c5d264a10e8a" />

#### 15. Monthly Outstanding Amount

**Purpose:** To track outstanding amounts by month.

**Interpretation:** Each month represents the total outstanding amount recorded for cases dated in that period.

**Business value:** The trend helps identify months with larger recorded balances.

**Recommended action:** Compare the monthly pattern with case volume, delinquency buckets, and recovered amounts. Confirm whether outstanding amounts represent opening balances, current balances, or case-level recorded amounts.

#### 16. Monthly Recovered Amount

**Purpose:** To monitor recovered value across the year.

**Interpretation:** The chart compares recovered amounts recorded from January through December 2024.

**Business value:** It highlights changes in monthly recovery value.

**Recommended action:** Investigate unusually high or low months and compare them with case volume, recovery methods, and delinquency mix.

#### 17. Monthly Legal Costs

**Purpose:** To understand how legal expenditure changes over time.

**Interpretation:** Each month's value represents the total recorded legal costs for cases dated in that month.

**Business value:** The trend helps monitor cost patterns throughout the reporting period.

**Recommended action:** Compare legal costs with recovered amounts and case complexity to assess cost efficiency. Do not assume that higher monthly costs directly caused a change in recoveries.

## Key Business Observations

The dataset contains 5,562 cases and records approximately $1.40 billion in outstanding amounts and $430.24 million in recovered amounts.

The amount recovery rate is approximately 30.72%, based on total recovered value divided by total outstanding value.

There are 1,132 cases marked Open and 1,095 marked Written Off. These status categories deserve separate monitoring because they represent different operational outcomes.

The average recorded Days Open is approximately 186.89 days. This measure can help frame an ageing analysis, although its interpretation depends on how the field was defined and whether it represents elapsed case age or another duration measure.

Regional recovery rates range from approximately 29.59% in the South Zone to 31.36% in the West Zone. These differences are descriptive and should be investigated alongside case mix, recovery methods, and outstanding balances.

Among the loan types, SME loans have the highest total recorded outstanding amount, at approximately $364.38 million. This reflects portfolio concentration, not necessarily weaker recovery performance.

## Recommendations

1. Monitor amount recovery rate alongside recovered and outstanding amounts.
2. Review open and written-off cases separately.
3. Compare recovery methods using recovery rates, legal costs, and case characteristics.
4. Investigate regional variation after accounting for delinquency mix and case volume.
5. Review monthly trends to identify changes in recorded recoveries and legal expenditure.
6. Add an ageing analysis to identify long-open cases requiring follow-up.
7. Establish recovery targets using approved business definitions and historical performance.

## Limitations

The analysis is based on the data available in the workbook. The meaning of outstanding amounts, Days Open, and case statuses should be confirmed before using the results for operational or financial decisions.

Recovery rates can be affected by differences in loan type, delinquency age, region, and recovery method. Observed associations do not prove causation.

The dataset's organization and agency names should be verified before describing it as real company data. Any illustrative or simulated data should be clearly identified as such.

## Conclusion

This project demonstrates how Excel can be used to summarize loan recovery operations, calculate financial KPIs, compare recovery methods, analyze outstanding balances, and monitor monthly trends.

The analysis supports a more structured view of recovery performance by combining financial amounts, case status, recovery methods, regional comparisons, and time-based reporting.

The key objective is to turn raw case data into useful questions and evidence-based recommendations for further investigation.

## Author

**Vansh Kumar**
Aspiring Data Analyst

**Skills:** Excel, data analysis, KPI reporting, business insights, and data visualization.


