## Wellness Program Statistics Report

## Project Overview

A company has recently implemented a new employee wellness program aimed at reducing employee stress levels and improving overall health. 
To answer this question, the company collected stress level data from employees before and after the implementation of the wellness program. 
The stress level data was collected using a self-reported 10-point scale, with higher scores indicating higher stress levels.
The business is interested in measuring the effectiveness of the wellness program in reducing stress levels, which can have implications for employee productivity, job satisfaction, and overall business performance.

### Data Source
Wellness program Data: Wellness program.xlsx file, containing detailed information about the stress level of employees from the company

### Tools
- Excel (Data Cleaning)
- Excel (Descriptive Analysis)
- Excel (Paired t-test)

### Data Cleaning/Preparation

- Data loading and Inspection
- Handling missing values

### Statistical Analysis

Using one-tailed test, paired t-test to measure the effectiveness of the wellness program in reducing stress levels.

### Descriptive statistics Analysis

Result: Pre-wellness Test

- Variable: Stress Level Before
- Sample Size: 15
- Mean: 7 The average value of the stress level before dataset.
- Median: 7 The middle value of the dataset.
- Mode: 8 indicating 8 as the value that appears more than once.
- Standard Deviation: 1.463850109 meaning that there is low variability considering that values cluster closely around the mean, data points are consistent.
- Kurtosis: 1.328205128 Kurtosis is Leptokurtic, because it is a positive kurtosis which indicates a higher peak.
- Skewness: 0 indicating a normal distribution.
- Observations:
  - The distribution is symmetric.
  - The standard deviation is relatively low, indicating less variability.


Result: Post-wellness Test

- Variable: Stress Level After
- Sample Size: 15
- Mean: 6.066667 The average value of the stress level after dataset.
- Median: 6 The middle value of the dataset.
- Mode: 6 indicating 6 as the value that appears more than once.
- Standard Deviation: 2.016598 meaning that there is low variability considering that values cluster closely around the mean, data points are consistent.
- Kurtosis: -0.19265 Kurtosis is Platykurtic, because it is a negative kurtosis which indicates a flatter distribution.
- Skewness: -0.10443 it is negatively mildly skewed to the left. Most values cluster around the average, fewer extreme values on the right side.
- Observations:
  - The standard deviation is approximately 2, indicating moderate variability.
  - The platykurtic distribution suggests lighter tails than a normal distribution.

Hypothesis Testing:
- H0: The stress level before the wellness program = the stress level after the wellness program
- H1: The stress level before the wellness program is > the stress level after the wellness program


Using a One-tailed test and Paired t-test to determine if the stress level before the wellness program is > the stress level after the wellness program
t-Test: Paired Two Sample for Means		

### Results/Findings

- P(T<=t) one-tail	0.082158949	
- t Critical one-tail	2.624494068	
- CI 99%
- Alpha Value 0.01
- P-Value 0.0821
- P-value (0.082158949) > Alpha value (0.01) indicating no strong evidence against the null hypothesis.
Therefore, we fail to reject the null hypothesis and conclude that the stress level before the wellness program = the stress level after the wellness program.

### Recommendations

1. Larger samples provide more reliable results.
2. Ensure accurate stress level measurements.
3. Account for potential confounding variables (e.g., demographics, external factors).
4. Assess stress levels over an extended period.

