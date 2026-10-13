## Study on Job Prospects in Technology & AI

### Data: [AI Jobs Market 2025-2026 | Salaries Dataset](https://www.kaggle.com/datasets/alitaqishah/ai-jobs-market-2025-2026-salaries)
This dataset was compiled from publicly available salary reports and job market research for 2025-2026. It includes data from Radio Global Salary Benchmark 2026, Robert Half Technology Salary Guide 2026, Motion Recruitment AI/ML Salary Report 2025, LinkedIn Workforce Insights 2025-2026, and Glassdoor AI Role Salary 2025. The salary figures are all in USD amounts and include base salary and standard bonuses. The emerging roles, such as, LLM Engineer, Rag Engineer, and AI Agent Developer were sourced from live job board aggregations on LinkedIn, Indeed, and Wellfound from 2025-2026. 

## Visualizations

- Salary Distribution by Job Title: box and whisker plot
- Faceted Distribution of Demand Score Across Experience Levels: histogram with KDE
- Average Job Demand Growth by Industry: bar chart
- Top 15 Most Demanded Skills in AI/Data Roles: bar chart
- Top 15 Highest Paying Skills: bar chart

## Modeling

### Random Forest Regressor

**Predicting annual salary for job postings** 
Target Variable: annual_salary_usd

**Model Results**
R-Squared: 0.6059 | RMSE: $46,103.46 | MAE: $38,265.60 | MAPE: 18.42%

### Random Forest Panel Regressor

**Predicting percentage of salary increase due to AI skills to base salary levels**
Target Variable: ai_salary_premium_pct

**Model Results**
R-Squared: 0.4016 | RMSE: 3.07% | MAE: 2.47%| MAPE: 23.58%

### K-Means Clustering

**Assessing career growth, security and automation risks**

**Model Results**
Silhouette coefficient: 0.2233 | Davies-Bouldin Index: 1.5809

### Regular Ridge Regression

**Predicting Salary for a Data Scientist**

**Model Results**
R-Squared: 0.6271 | MAE: $18,736.80 | RMSE $22,428.59 | Optimal Alpha: 1.00 | Duan’s Smearing Factor: 1.002113| Sample Size: 46
