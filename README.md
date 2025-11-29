Customer Behaviour Analysis  
Executive Summary 
This project executes a full-cycle data analysis pipeline to understand customer shopping 
habits, revenue drivers, and product performance. The solution involves data extraction 
and cleaning using Python, strategic analysis using SQL, and interactive reporting using 
Power BI. 
The analysis focuses on a dataset of 3,900 customers, uncovering critical insights 
regarding subscription inefficacy, gender-based revenue dominance, and opportunities for 
loyalty programs. 
Project Structure 
├── data/ 
│   └── shopping_behavior_updated.csv    # Raw dataset 
├── notebooks/ 
│   └── Customer Behaviour Analysis.ipynb # Python data cleaning & 
feature engineering 
├── sql/ 
│   └── customer_behaviour_analysis.sql   # SQL queries for business 
questions 
├── dashboard/ 
│   └── Customer Behaviour Dashboard.pbix # Interactive Power BI 
dashboard 
└── README.md 
Methodology & Tech Stack 
Phase I: Data Extraction & Transformation (Python) 
File: Customer Behaviour Analysis.ipynb 
• Library: pandas 
• Process: 
o Loaded raw CSV data. 
o Performed statistical audits to ensure data integrity (checking for nulls, 
distributions). 
o Feature Engineering: 
▪ Standardization: Renamed columns (e.g., Purchase Amount 
(USD) → purchase_amount). 
▪ Age Grouping: Created buckets (Young Adult, Adult, Middle
aged, Senior) using pd.qcut. 
▪ Frequency Mapping: Converted text frequencies (e.g., 
"Fortnightly") to numeric values. 
Phase II: Strategic Business Analysis (SQL) 
File: customer_behaviour_analysis.sql 
• Objective: Executed queries to answer specific business questions regarding
