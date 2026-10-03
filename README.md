# Diabetes Risk Analysis (Tableau)

**Author:** Doan Duy Minh Nguyen
**Course:** ISOM 845, Suffolk University (Sawyer Business School), Midterm Project
**Tools:** Tableau
**Interactive version:** [paste your Tableau Public link]

## Project Overview

This project analyzes medical data on 2,768 patients to find which health indicators best separate diabetic from non-diabetic patients. I built Tableau views comparing glucose, BMI, age, insulin, and blood pressure by diabetes outcome.

I chose this topic because diabetes is closely linked to excess weight, and obesity is a major health issue in the US. The analysis shows which measurements matter most when assessing risk.

## Objective

Analyze medical indicators to determine which variables differentiate diabetic and non-diabetic patients.

## Dataset

- **Source:** Healthcare-Diabetes dataset [https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data]
- **Records:** 2,768 patients (952 diabetic, 1,816 non-diabetic)
- **Key fields:** glucose, BMI, age, insulin, blood pressure, and diabetes outcome
- **Data preparation:** created a binned blood pressure field in Tableau

## Visualizations

- Total patients, total diabetic patients, and total non-diabetic patients
- Distributions of glucose, BMI, age, and insulin by diabetes outcome
- Average BMI, glucose, and insulin by outcome
- Comparison of health indicators by diabetes outcome
- Scatter plot of glucose vs. BMI


## Key Findings

- Diabetic patients have significantly higher glucose levels, making glucose the strongest indicator of diabetes risk.
- BMI is slightly higher among diabetic patients, which suggests a moderate relationship between body weight and diabetes.
- The scatter plot shows a positive relationship between glucose and BMI, but glucose has a much stronger link to diabetes outcome.
- Diabetic patients are older on average, which indicates that risk increases with age.
- Insulin levels vary widely and show less clear patterns, partly because of missing or zero values in the dataset.
- Overall, glucose is the most important factor, while BMI and age contribute moderately.

## Limitations

- The analysis shows associations, not causes.
- Missing or zero insulin values limit what can be concluded about insulin.
- The dataset covers a limited group of patients, so the results may not apply to other populations.
