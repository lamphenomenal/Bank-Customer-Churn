 # Bank Customer Churn & Segmentation Analysis
 ## Project Overview

Customer churn is a major revenue risk in retail banking. This project analyzes customer demographics and account behavior to identify churn drivers, predict churn risk, and segment customers into actionable groups.

Beyond prediction, the project translates analytics into marketing strategy recommendations suitable for senior leadership (CMO-level).

## Objectives

Identify attributes more common among churners than non-churners

Predict customer churn using machine learning

Understand demographic and geographic differences in customer behavior

Segment customers into meaningful groups

Recommend targeted marketing packages for each segment

## Dataset

~10,000 bank customers

Features include:

Demographics (Age, Gender, Geography)

Account behavior (Balance, Products, Activity, Tenure)

Financial indicators (Credit Score, Estimated Salary)

Target variable: Exited (Churn)

## Exploratory Data Analysis (EDA)

Key insights from EDA:

Overall churn rate ≈ 20%

Churn increases significantly after age 40

German customers churn ~2x more than French and Spanish customers

Inactive customers and single-product holders show higher churn

High-balance customers churn more than low-balance customers

## Predictive Modeling
Models Used

Logistic Regression (baseline)

Random Forest Classifier (final model)

Model Performance (Random Forest)

ROC AUC: ~0.87

Churn Recall: ~45%

Significant improvement over baseline logistic regression

Top Churn Drivers

Age

Balance

Estimated Salary

Credit Score

Number of Products

Customer Activity

## Customer Segmentation

Using KMeans clustering + PCA, customers naturally split into two primary segments:

Segment 1 — Everyday Bankers

Younger customers

Lower balances

Multiple products

High engagement

Lower churn (~16%)

Segment 2 — Affluent Floaters

Older customers

High balances

Few products

Lower engagement

Higher churn (~24%)

## Business Recommendations
## Recommended Marketing Packages

1. Digital Growth Bundle (Everyday Bankers)

Fee-free checking

Credit card rewards

Mobile-first incentives
 Goal: Increase products per customer & lifetime value

2. Premier Retention Program (Affluent Floaters)

Personalized relationship management

Preferential savings & investment products

Loyalty benefits
 Goal: Reduce churn among high-value customers

3. Market-Specific Strategy

Germany: Retention-focused approach

France & Spain: Growth and cross-sell focus

## Tools & Technologies

Python (Pandas, NumPy, Scikit-learn)

Matplotlib / Seaborn

PCA & KMeans Clustering

Random Forest Classification

## Key Takeaway

The value of analytics lies not in the model itself, but in the strategic decisions it enables.

This project demonstrates how data science can move beyond prediction to drive actionable marketing and retention strategies in banking.

## Contact

Feel free to connect or reach out for discussions on:

Customer analytics

Churn modeling

Banking strategy & marketing analytics
