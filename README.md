# gender-equity

# Gender Wage Gap Analysis

## Overview
This project analyzes the gender wage gap across countries using the OECD Gender Inequality Database. The main focus is comparing wage disparities between Korea and Latvia, with statistical analysis and visualization to understand patterns and suggest recommendations.

## Dataset
The dataset used is `Gender.csv`, which contains median earnings of men and women for various countries (2022).

Columns of interest:
- `% of median earnings of men, 2022`

## Analysis Performed
1. **Data Cleaning**
   - Dropped missing values
   - Converted wage gap column to numeric

2. **Descriptive Statistics**
   - Mean, Median, Mode, Variance, Standard Deviation

3. **Visualization**
   - Histogram showing the distribution of gender wage gap percentages

4. **Statistical Tests**
   - Shapiro-Wilk test for normality
   - Levene’s test for equal variance between country groups
   - Independent t-test to compare wage gap means

5. **Country Comparison**
   - Example groups: Korea & Japan vs. Latvia & Israel
   - Analysis focused on Korea vs. Latvia

## Key Findings
- The t-test revealed no statistically significant difference in the gender wage gap between Korea and Latvia (p-value = 0.615).
- Despite no significant difference, gender wage gaps persist and require targeted interventions.

## Recommendations
- Mentorship and leadership programs for women
- Bias-free recruitment and promotion processes
- Awareness campaigns to challenge stereotypes
- Flexible work policies to reduce career interruptions

## Requirements
Python 3.x with the following libraries:
