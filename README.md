# TikTok Classification Project

## Author: Abd Ur Rehman
## Date: 16/06/2023

## Table of Content

- [Project Overview](#project-overview)
- [Results and Findings](#results-and-findings)
- [Recommendation](#recommendations)

### Project Overview
---
This data science project focuses on classifying TikTok content using advanced statistical methods and hypothesis testing. The primary goal is to applying rigorous statistical techniques to address the classification problem related to TikTok data.

### Project Purpose
---
The purpose of this project is to demonstrate proficiency in preparing, creating, and analyzing hypothesis tests and statistical methods in the context of the TikTok classification project.

### Data Source
---
The dataset used in this project is secondary data obtained from Google. It includes TikTok-related data,

### Tools
---
- Jupyter Notebook
- Python
- python libraries
  - Numpy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scipy.stats

### Data Cleaning/Preparation
---
In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspections.
2. Handling missing values.
3. Data cleaning and formatting.

## Hypothesis Test

In this project, we conduct a two-sample t-test to investigate potential differences in verified status column

- **$H_0$**: There is no difference in number of views between TikTok videos posted by verified accounts and TikTok videos posted by unverified accounts (any observed difference in the sample data is due to chance or sampling variability).

- **$H_A$**: There is a difference in number of views between TikTok videos posted by verified accounts and TikTok videos posted by unverified accounts (any observed difference in the sample data is due to an actual difference in the corresponding population means).

### Results and Findings

Based on the analysis of the dataset, the following key findings were observed:

- The p-value for the t-test (pvalue=2.6088823687177823e-120) is extremely small, indicating a high level of statistical significance.
- With a p-value much smaller than the significance level of 5%, we reject the null hypothesis.

These findings lead to the following conclusions:

- There is a statistically significant difference in the mean video view count between verified and unverified accounts on TikTok.
- The analysis reveals that videos from verified accounts tend to have a significantly different average view count compared to videos from unverified accounts.

This suggests potential fundamental behavioral differences between these two groups of TikTok accounts.

### Recommendations

Based on the observed statistically significant difference in average view counts between videos from verified and unverified accounts, it is recommended to explore the underlying factors contributing to this behavioral difference. Consider the following next steps:

- Investigate the root causes of this difference, such as whether unverified accounts tend to post clickbait content or if they are associated with view count manipulation through spam bots.
- Explore the creation of a regression model focused on the 'verified_status' variable. A regression model can provide insights into user behavior within the group of verified users.
- The regression model can help analyze and predict behaviors and characteristics associated with verified accounts, leading to a deeper understanding of the factors influencing user interactions and engagement on TikTok.

Continuing the analysis with these recommendations can provide valuable insights and inform strategies for content creators and platform administrators on TikTok.

### Limitations

I had to remove all Null values from data because they would have affected the accuracy of my conclusions from the Hypothesis testing.
