# Attrition Analysis Using Python

## Project Overview

Employee attrition is a major challenge for organizations because high turnover can increase recruitment costs, reduce productivity, and impact team performance.

This project uses Python and statistical hypothesis testing to analyze factors associated with employee attrition using an HR analytics dataset. The goal is to identify patterns that may help organizations improve employee retention.

---

## Business Problem

Why do employees leave an organization?

This project investigates whether certain workplace factors are significantly associated with employee attrition by applying data analytics and statistical testing techniques.

---

## Dataset

The dataset contains information on 1,470 employees and 35 HR-related features, including:

* Age
* Department
* Monthly Income
* Job Satisfaction
* Work-Life Balance
* Overtime Status
* Years at Company
* Attrition Status

Dataset Size: **1,470 rows × 35 columns**

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

## Methodology

### 1. Data Preparation

* Loaded and explored the dataset
* Checked for missing values
* Checked for duplicate records
* Verified data quality

### 2. Exploratory Data Analysis (EDA)

* Examined employee attrition distribution
* Analyzed overtime patterns
* Compared salary distributions between employee groups
* Created visualizations to support findings

### 3. Statistical Hypothesis Testing

#### Hypothesis 1: Overtime vs Attrition

**Null Hypothesis (H₀):**
There is no association between overtime work and employee attrition.

**Alternative Hypothesis (H₁):**
There is a significant association between overtime work and employee attrition.

**Test Used:** Chi-Square Test of Independence

**Results:**

* Chi-Square Statistic = 87.56
* P-value = 8.16 × 10⁻²¹

**Conclusion:**
The null hypothesis was rejected. Employees working overtime were significantly more likely to leave the company.

---

#### Hypothesis 2: Monthly Income vs Attrition

**Null Hypothesis (H₀):**
There is no difference in average monthly income between employees who leave and employees who stay.

**Alternative Hypothesis (H₁):**
There is a significant difference in average monthly income between employees who leave and employees who stay.

**Test Used:** Independent Samples T-Test

**Results:**

* T-Statistic = -6.20
* P-value = 7.15 × 10⁻¹⁰

**Conclusion:**
The null hypothesis was rejected. Employees who left the company had significantly lower average monthly incomes.

---

## Key Findings

### Finding 1: Overtime Increases Attrition Risk

Employees working overtime experienced an attrition rate of approximately **30.5%**, compared to **10.4%** among employees who did not work overtime.

### Finding 2: Lower Income is Associated with Higher Attrition

Employees who left the organization earned substantially lower salaries on average than employees who remained.

---

## Business Recommendations

Based on the analysis:

1. Monitor teams with excessive overtime to reduce burnout risk.
2. Review compensation structures for lower-paid employee groups.
3. Improve workload distribution and work-life balance initiatives.
4. Use attrition analytics as part of workforce planning and retention strategies.


## Author

Arpita

Data Analytics & Data Science Portfolio Project

