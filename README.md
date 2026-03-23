# Task 3: A/B Testing & Hypothesis Testing

**Internship:** Soft Nexis Technology  
**Intern Name:** Shubham Jaiswal  
**Intern ID:** SN1001074  
**Domain:** Data Science & Machine Learning Using Python  

---

## Overview

This project performs a complete A/B testing workflow on a real e-commerce dataset to determine whether a new webpage design significantly improves user conversion rates.

---

## Dataset

- **File:** `dataset/ab_data.csv`
- **Rows:** ~294,000
- **Columns:** user_id, timestamp, group, landing_page, converted

---

## Project Structure
```
AB_Testing/
├── dataset/
│   └── ab_data.csv
├── images/
│   ├── ci_plot.png
├── ab_testing_hypothesis.ipynb
└── README.md
```

## Libraries Used

- pandas
- numpy
- matplotlib
- scipy
- statsmodels

---

## What's covered

- Data loading and cleaning
- Hypothesis formulation
- Two-Proportion Z-Test
- Confidence Interval Visualization
- Chi-Square Test
- Independent T-Test
- Power Analysis
- Final Summary
