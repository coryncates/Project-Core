
# Adult Income Analysis README

## Table of Contents

- [Business Problem and Stakeholders](#business-problem-and-stakeholders)
- [Source of Data](#source-of-data)
- [Description of Data](#description-of-data)
- [Analytical Insights](#analytical-insights)
- [Metrics for the Best Model](#metrics-for-the-best-model)
- [Model Effectiveness in Solving the Business Problem](#model-effectiveness-in-solving-the-business-problem)
- [Summary and Recommendations](#summary-and-recommendations)

## Business Problem and Stakeholders

**Business Problem:**  
The primary objective of this analysis is to predict whether an individual's income exceeds $50K per year. This information can be vital for various financial and governmental organizations, as it can help them tailor their services, policies, and marketing strategies to cater to different income groups more effectively.

**Stakeholders:**  
- **Financial Institutions:** Banks, credit unions, and other lending institutions can use this information to gauge the creditworthiness of potential borrowers or to tailor specific financial products to different income brackets.
- **Governmental Agencies:** Understanding the distribution of income can assist in policy-making, especially in areas like taxation, welfare, and public services.
- **Marketing and Advertising Agencies:** With insights into the income levels of different demographic groups, these agencies can design more targeted and effective marketing campaigns.

## Source of Data
The dataset used for this analysis originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult), a well-known source for machine learning datasets.

## Description of Data
The Adult Income dataset comprises 48,842 entries, each with 15 attributes. These attributes capture various aspects of an individual's demographics and financial status, such as age, education level, race, gender, hours worked per week, and more. The primary attribute of interest is `income`, which indicates whether an individual's annual income is above or below $50K.

## Analytical Insights

#### 4.1 Income Distribution by Race
![RaceIncome](https://github.com/coryncates/Project-Core/blob/main/RaceIncome.png)

**Interpretation:**  
From the "Income Distribution by Race" plot, it's evident that there are disparities in income distribution across different racial groups. Some racial groups have a higher proportion of individuals earning above $50K compared to others. It's crucial for stakeholders to recognize these disparities and ensure that policies and strategies are equitable across all racial groups.

#### 4.2 Income Distribution by Gender
![IncomeGender](https://github.com/coryncates/Project-Core/blob/main/IncomeGender.png)

**Interpretation:**  
The "Income Distribution by Gender" plot highlights a noticeable difference in income distribution between males and females. Males tend to have a higher proportion of individuals earning above $50K compared to females. This observation underscores the importance of addressing gender income disparities in various sectors, from workplaces to policy-making.

## Metrics for the Best Model
Our best model, with a recall macro avg of .77, found our best hyperparameter settings for our logistic regression model would be solver='saga', penalty='elasticnet,' and l1_ratio=0.1. An l1 ratio of .1 means that the model used a combination of l1 and l2 regularization.

## Model Effectiveness in Solving the Business Problem
The model's performance metrics indicate that it can reliably predict whether an individual's income exceeds $50K per year. This prediction capability can be instrumental for our stakeholders in making informed decisions and strategies tailored to different income groups.

## Summary and Recommendations

Based on our model's performance and the analytical findings:

1. **For Financial Institutions:** Given the disparities in income distribution across race and gender, financial products and services should be designed with these disparities in mind to cater effectively to all demographic groups.
2. **For Governmental Agencies:** Policies related to taxation, welfare, and public services should consider the income disparities observed across different racial and gender groups. This can help in ensuring equitable policies and services for all citizens.



