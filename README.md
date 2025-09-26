# Project Overview
I applied Exploratory Data Analysis (EDA) on a banking dataset to uncover insights into customer demographics, financial behavior, and risk factors, supporting data-driven decisions in credit risk management.
## Problem Statement
- Develop a deep understanding of risk analytics in banking. The goal is to use customer profile data to:
- Analyze financial behavior.
- Predict credit default risks.
- Optimize lending decisions.
---
### Key Components
- Exploratory Data Analysis (EDA): Understand customer trends, segment risks.
- Feature Engineering: Prepare and transform raw features into predictive inputs.
- Business Insight Generation: Convert technical findings into actionable recommendations.

 ### Data Cleaning
- Checked and confirmed no missing values.
- Converted 'Joined Bank' column to datetime format.
- Ensured data types were consistent across all features.

  
### Questions Addressed
- What is the demographic distribution (age, nationality, occupation)?
- How do income bands influence customer behavior?
- What are the counts of key categorical features (risk weighting, loyalty classification)?
- Are there missing values?
- What are the descriptive statistics of numerical variables?

  ### EDA Techniques Used
- Value counts for categorical variables.
- Descriptive stats using .describe().
- Visualization using Matplotlib and Seaborn.
- Analysis of patterns by income bands, product types, and risk classification.

  ### Findings
- Demographics: Clear segmentation by age, nationality, and occupation.
- Income Bands: Distribution across low, mid, and high-income brackets.
- Categorical Counts: Distribution of risk weights, fee types, and loyalty groups.
- Numerical Summary: Mean, median, standard deviation of financial attributes.
## 🔍 Key Findings from Heatmap
- `Loan Amount` is highly correlated with `Total Income` (r = 0.82)
- `Credit Score` shows a negative correlation with `Risk Weight`, suggesting higher risk with lower scores
- Weak correlation between `Age` and `Loan Default` indicates age is not a strong predictor alone


  ### Limitations
 - Dataset may contain biases (e.g., underrepresented demographics).
- Analysis limited to available features; no modeling applied.
- No advanced statistical tests conducted.

### Data Source
 CSV file: Banking.csv containing detailed customer information

### Technologies Used
- Excel – Preliminary data cleanup.
- SQL – Table creation and data structuring.
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn) – Data preparation and EDA.
- Jupyter Notebook – Development environment.

### Conclusion
This project lays the foundation for risk profiling in banking by analyzing customer data. It uncovers trends that can be used to improve lending strategies and enhance credit risk assessment.









