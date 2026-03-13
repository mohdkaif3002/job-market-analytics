# Job Market Analytics Dashboard 2024

Analyzed 14,199 data science job postings across 74 countries to uncover salary trends, hiring patterns, and remote work insights using Python, Excel, and Power BI.

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn) — EDA and visualizations
- **Microsoft Excel** — Data cleaning and pivot tables
- **Power BI** — Interactive dashboard

## Dataset
- Source: [Data Science Jobs 2024 — Kaggle](https://www.kaggle.com/datasets/murilozangari/jobs-and-salaries-in-data-field-2024)
- 14,199 records across 12 columns
- Zero missing values

## Key Insights
- Average salary across all roles: **$149,472**
- Top paying roles: Analytics Engineering Manager, Data Science Manager
- **United States** dominates hiring with the most job postings
- Only **32.2%** of jobs are fully remote
- Senior-level roles average **$163K+** vs Entry-level at ~$90K
- Large companies pay significantly more than small companies

## Project Structure
```
job-market-analytics/
├── charts/          # 5 EDA visualizations (PNG)
├── data/            # Raw CSV + cleaned Excel file
├── Dashboard/       # Power BI .pbix file
├── notebook/        # Jupyter notebook (EDA)
└── README.md
```

## Dashboard Preview
![Dashboard](charts/chart1_top_paying_jobs.png)

## Visualizations
1. Top 10 Highest Paying Job Titles
2. Salary Distribution by Experience Level
3. Remote Work Trend (2020–2024)
4. Top 10 Hiring Countries
5. Company Size vs Average Salary
