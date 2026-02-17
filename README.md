Telco Customer Churn Analysis
📊 Business Problem
A telecom company is experiencing 26% annual customer churn, resulting in significant revenue loss. The goal is to identify high-risk customer segments and understand key churn drivers to design targeted retention strategies.

📈 Key Insights
Month-to-month contracts: 43% churn rate (vs 3% for 2-year contracts)

Fiber optic internet: 42% churn (vs 19% DSL)

High MonthlyCharges + short tenure: highest risk segment

Estimated revenue impact: 3% churn reduction could save ₹X lakhs annually

🛠️ Tech Stack
Python: Pandas, Scikit-learn (EDA + Random Forest)

Power BI: Interactive 3-page dashboard

Dataset: Telco Customer Churn (Kaggle) – 7,043 customers
​
🎯 Analysis Process
1. Exploratory Data Analysis
text
Key findings:
✓ Churn rate: 26.5% (1,869/7,043 customers)
✓ Top churn drivers: Contract type, Internet service, Monthly charges
✓ High-value customers (high charges) churn at 23% rate
2. Predictive Modeling
text
Model: Random Forest
Accuracy: 81%
Precision (Churn): 78%
Recall (Churn): 82%
Top features:
1. Tenure (months)
2. MonthlyCharges
3. Contract type
4. InternetService
3. Dashboard Features
3 interactive pages: Overview, Segments, Actionable insights

Filters: Contract, tenure, charges, service type

What-if analysis: Churn reduction impact

KPIs: Churn rate, revenue at risk, segment analysis

💡 Business Recommendations
Convert contracts: Offer incentives for month-to-month → annual/2-year

Improve fiber optic: Service quality issues driving 42% churn

Target high-risk: Early intervention for high charges + short tenure customers

Pricing strategy: Review pricing for high-churn segments

📊 Dashboard Preview
🔗 Live Demo
<img width="1272" height="717" alt="image" src="https://github.com/user-attachments/assets/1961de52-fcd4-4415-bba2-d5c4c356ac17" />
<img width="1271" height="717" alt="image" src="https://github.com/user-attachments/assets/444137cf-c30f-40b5-bfad-94b30ac5319f" />

📈 Results Summary
Metric	Value
Dataset Size	7,043 customers
Churn Rate	26.5%
Model Accuracy	81%
Potential Revenue Saved	₹X lakhs/year
🎓 Skills Demonstrated
Data cleaning & EDA (Pandas, Matplotlib)

Classification modeling (Logistic Regressio)

Interactive dashboarding (Power BI)

Business storytelling & impact quantification

📚 Dataset Source
Telco Customer Churn - Kaggle
​
