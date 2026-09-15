# Rate-Of-Cancer-Cases-Before-And-After-The-Chernobyl-Disaster-In-April-1986

## 📊 Project Overview

This project analyses cancer case data recorded in **1985 and 1986** across three locations:

- Belarus
- Gomel
- Mogilev

The dataset also separates cases by:

- Sex
- Cancer type
- Year
- Location
- Number of cases

The analysis uses **Microsoft Excel PivotTables** to identify patterns, compare cancer types, examine changes between years, and evaluate differences by sex and geographical location.

---

## 🎯 Project Objectives

The main objectives of this analysis are to:

1. Identify the cancer types with the highest number of recorded cases.
2. Compare total cases between 1985 and 1986.
3. Examine differences in cancer cases between men and women.
4. Compare cancer cases across Belarus, Gomel, and Mogilev.
5. Determine which cancer types experienced the largest increases between 1985 and 1986.
6. Identify the locations with the highest recorded number of cases.
7. Examine the distribution of cancer types by sex.
8. Compare cancer patterns across locations and years.
9. Identify cancer categories that require further investigation.
10. Develop data-driven recommendations from the analysis.

---

# ❓ Questions, Answers & Analysis

## Question 1
### Which cancer type recorded the highest total number of cases?

**Answer: Lung cancer**

| Cancer Type | Total Cases |
|---|---:|
| Lung | **361.1** |
| Skin | **219.8** |
| Rectum | 100.3 |
| Colon | 81.1 |
| Pancreas | 64.4 |
| Kidney | 44.9 |
| Thyroid | 26.2 |

### Analysis

Lung cancer recorded the highest total number of cases at **361.1**, considerably higher than the other cancer categories.

Lung cancer therefore represents the most prominent cancer category in this dataset and should receive particular attention in further analysis.

---

## Question 2
### How did the total number of recorded cases change between 1985 and 1986?

| Year | Total Cases |
|---|---:|
| 1985 | **376.8** |
| 1986 | **521.0** |

### Answer

Total recorded cases increased from **376.8 in 1985 to 521.0 in 1986**.

### Percentage Increase

\[
\frac{521.0 - 376.8}{376.8} \times 100
= 38.3\%
\]

**Total cases increased by approximately 38.3%.**

### Analysis

The increase is substantial and suggests that the change between the two years should be investigated further, particularly by cancer type, sex, and location.

---

## Question 3
### Which cancer type experienced the largest percentage increase between 1985 and 1986?

| Cancer Type | 1985 | 1986 | % Increase |
|---|---:|---:|---:|
| Thyroid | 6.4 | 19.8 | **209.4%** |
| Kidney | 14.5 | 30.4 | 109.7% |
| Colon | 32.4 | 48.7 | 50.0% |
| Pancreas | 28.0 | 36.4 | 30.0% |
| Rectum | 42.2 | 58.1 | 37.7% |
| Lung | 146.7 | 214.4 | 46.1% |
| Skin | 106.6 | 113.2 | 6.2% |

### Answer

**Thyroid cancer recorded the largest percentage increase, approximately 209.4%.**

### Analysis

Although thyroid cancer had the smallest overall number of cases, its percentage increase was the largest. This demonstrates why both **absolute totals and percentage changes** should be examined.

---

## Question 4
### Which cancer type had the largest absolute increase in cases?

### Answer

**Lung cancer**

Lung cancer increased from:

- 1985: **146.7**
- 1986: **214.4**

Absolute increase:

\[
214.4 - 146.7 = 67.7
\]

Therefore, lung cancer increased by **67.7 cases**, the largest absolute increase among the cancer categories.

### Analysis

This is different from the percentage-growth result. Thyroid cancer had the largest percentage increase, while lung cancer had the largest numerical increase.

---

## Question 5
### Which sex recorded the highest number of cases?

| Sex | Total Cases |
|---|---:|
| Men | **638.9** |
| Women | 258.9 |

### Answer

**Men recorded the highest total number of cases.**

Men accounted for approximately:

\[
\frac{638.9}{897.8} \times 100
\approx 71.2\%
\]

of the total recorded cases.

Women accounted for approximately **28.8%**.

### Analysis

The dataset shows a substantial difference between the recorded cases for men and women. Further investigation should examine whether this difference varies by cancer type and location.

---

## Question 6
### Which location recorded the highest total number of cases?

| Location | Total Cases |
|---|---:|
| Mogilev | **323.1** |
| Belarus | 295.0 |
| Gomel | 279.7 |

### Answer

**Mogilev recorded the highest total number of cases at 323.1.**

### Analysis

Mogilev had the highest total among the three locations represented in the dataset.

However, the dataset labels Belarus alongside Gomel and Mogilev, so the geographical categories should be interpreted carefully. Belarus may represent a national-level aggregate while Gomel and Mogilev represent specific locations.

---

## Question 7
### Which cancer type was most prominent among men?

For men, the recorded totals were:

| Cancer Type | Male Cases |
|---|---:|
| Lung | **332.1** |
| Skin | 120.4 |
| Rectum | 58.4 |
| Pancreas | 45.0 |
| Colon | 46.0 |
| Kidney | 30.0 |
| Thyroid | 7.0 |

### Answer

**Lung cancer was the most prominent cancer type among men.**

### Analysis

Lung cancer accounts for a substantially larger share of the male cases than any other cancer category.

---

# 📈 Key Findings

The analysis produced several important findings:

### 1. Lung cancer dominates the dataset

Lung cancer recorded **361.1 cases**, making it the largest cancer category.

### 2. Overall cases increased significantly

Recorded cases increased from **376.8 in 1985 to 521.0 in 1986**, representing an increase of approximately **38.3%**.

### 3. Thyroid cancer experienced the fastest growth

Thyroid cancer increased by approximately **209.4%**, despite having the lowest overall case total.

### 4. Men recorded substantially more cases

Men accounted for approximately **71.2%** of the recorded cases, compared with approximately **28.8% for women**.

### 5. Mogilev recorded the highest total

Mogilev recorded **323.1 total cases**, followed by Belarus at 295.0 and Gomel at 279.7.

### 6. Cancer patterns differ by sex

- Men: **Lung cancer** was dominant.
- Women: **Skin cancer** was dominant.

---

# 🔍 PivotTable Analysis Used

The Excel workbook contains several PivotTable analyses.

## PivotTable 1 — Year vs Cancer Type

**Rows:** Year  
**Columns:** Cancer Type  
**Values:** Sum of Cases

This PivotTable was used to determine how cancer cases changed between 1985 and 1986.

---

## PivotTable 2 — Sex vs Cancer Type

**Rows:** Sex  
**Columns:** Cancer Type  
**Values:** Sum of Cases

This analysis identified differences between male and female cancer patterns.

---

## PivotTable 3 — Cancer Type vs Year

**Rows:** Cancer Type  
**Columns:** Year  
**Values:** Sum of Cases

This PivotTable was used to calculate absolute and percentage changes.

---

## PivotTable 4 — Location and Sex

**Rows:** Sex and Location  
**Columns:** Cancer Type  
**Values:** Sum of Cases

This analysis allows cancer patterns to be compared simultaneously by sex, location, and cancer type.

---

## PivotTable 5 — Location × Year × Cancer Type

The most detailed PivotTable combines:

- Location
- Year
- Cancer Type
- Cases

This allows users to drill down into individual geographical and temporal patterns.

---

# 📊 Data Summary

| Variable | Categories |
|---|---|
| Years | 1985, 1986 |
| Sex | Men, Women |
| Locations | Belarus, Gomel, Mogilev |
| Cancer Types | Colon, Kidney, Lung, Pancreas, Rectum, Skin, Thyroid |
| Total Recorded Cases | **897.8** |

---

# 💡 Recommendations

Based on the analysis, the following recommendations are proposed:

### 1. Investigate lung cancer as a priority

Lung cancer has the highest total number of recorded cases and the largest absolute increase between the two years.

### 2. Investigate the rapid increase in thyroid cancer

The **209.4% increase** is substantially higher than that of the other cancer categories and warrants further investigation.

### 3. Conduct sex-specific analysis

Because the cancer patterns differ considerably between men and women, future analysis should examine risk patterns separately by sex.

### 4. Investigate geographical differences

Mogilev recorded the highest overall total. Further analysis should determine whether this pattern remains consistent across individual cancer types and years.

### 5. Expand the time period

The current dataset covers only **two years**. Adding additional years would make it possible to identify longer-term trends rather than relying on a single year-to-year comparison.

### 6. Use rates where population data are available

The current analysis uses recorded `cases`. If population figures are available, calculate **cases per population size** to make comparisons between locations and groups more meaningful.

### 7. Build an interactive dashboard

A future version could include:

- Total cases KPI
- Cases by cancer type
- Year-over-year growth
- Cases by sex
- Cases by location
- Cancer type trend
- Location comparison
- Interactive slicers for year, sex, location, and cancer type

---

# ⚠️ Data Limitations

Several limitations should be considered when interpreting the results:

- The dataset covers only **1985 and 1986**.
- There are only three geographical categories.
- The dataset records cases but does not provide population denominators.
- The analysis is descriptive and does not establish causation.
- The reason for the large differences between groups cannot be determined from the available variables alone.
- `Belarus` appears alongside `Gomel` and `Mogilev`, so the geographical hierarchy should be clarified before making population-level comparisons.

---

# 🛠️ Tools Used

- Microsoft Excel
- Excel PivotTables
- PivotTable filtering
- Percentage-change calculations
- Descriptive data analysis
- Data visualization

---

# 📁 Project Structure

```text
Project Data Analysis/
│
├── Project Data analysis.xlsx
└── README.md
