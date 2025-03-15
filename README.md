ISS Board of Directors History Analysis 🚀
📊 Project Overview
Unlock the story behind the numbers with a deep dive into board compositions and their impact on company performance. This project leverages data from ISS Board of Directors, Compustat, and WRDS IBES to explore:

The influence of demographic and employment factors on financial metrics like revenue, net income, and ROA.
Industry and sectoral trends shaping corporate governance over time.
The diversity representation on corporate boards and its connection to financial success.
🔑 Key Features
1. Data Preparation 🔄
Datasets Used:

ISS Board of Directors Dataset
Compustat Company Financials
WRDS IBES Operations
Data Cleaning Techniques:

Missing Values: Handled using median imputation.
Feature Engineering: One-hot encoding for attributes like ethnicity and job titles.
Merging: Combining multi-source data for richer analysis.
2. Exploratory Data Analysis (EDA) 📈
Trends in Board Composition:

Age distribution shows a dominance of board members in the 60-70 age group.
Female representation surged by 150% in the Consumer Discretionary sector since 2008.
Sectoral Trends:

The Healthcare sector saw a dramatic revenue increase post-2019, reflecting the pandemic's impact.
A steady rise in the number of outside public board members across industries.
Ethnicity Representation:

A dominance of Caucasian directors signals a need for greater diversity in leadership.
3. Econometric Analysis 🧮
Dependent Variables:
Total Revenue (Revt)
Net Income (NI)
Return on Assets (ROA)
Key Findings:
Revenue Insights:

Board members with CEO/Chairman roles contribute an impressive $1.5 to $2.3 billion to company revenue.
Female representation adds around $1.87 billion in revenue.
Ethnic diversity (especially Black, Hispanic, and Indian directors) correlates with higher revenue generation.
Net Income Insights:

CEO and Chairman roles add approximately $143 to $285 million to net income.
Female representation boosts net income by $154 million.
Presidents on the board have a negative impact on net income.
ROA Insights:

CEO and Chairman presence significantly boosts ROA.
Female representation leads to a positive effect on ROA.
Presidents on the board negatively impact ROA.
🔧 Technologies Used
Programming Languages: Python
Libraries: pandas, NumPy, PyFixest, statsmodels, scikit-learn, matplotlib
Cloud Services: Google Cloud Storage (BigQuery for data storage and analysis)
