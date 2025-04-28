# -Customer-Churn-Analysis-of-Telecom-Company
This project focuses on understanding customer churn, which refers to the rate at which customers end their subscriptions. Using data analysis and visualization techniques, I aim to identify patterns and reasons for churn, providing actionable insights for retention strategies.

🎯 **Objective**
Explore and clean the customer churn dataset.
Analyze the distribution of churn across different customer features.
Identify key factors associated with customer churn.
Provide recommendations to reduce churn.

🧰 **Tools and Libraries**
Python
Pandas for data manipulation
NumPy for numerical operations
Seaborn and Matplotlib for data visualization

📊 **Data Cleaning Steps**
Replaced blank values in TotalCharges with 0 and converted it to float.
Verified no missing values were left after cleaning.
Converted the SeniorCitizen column from numeric (0/1) to categorical ("No"/"Yes").
Checked and confirmed no duplicate customerID entries.

**🔎 Key Analyses and Visualizations**
Churn Distribution
Overall churn percentage visualized.
Churn by Senior Citizen Status
Compared churn rates between senior citizens and non-senior citizens.
Churn by Gender
Analyzed if gender impacts churn.
Churn by Internet Service
Identified the effect of internet services on churn probability.
Churn by Contract Type
Month-to-month contracts show the highest churn.
Churn by Tenure
Customers with shorter tenure tend to churn more.
Churn by Payment Method
Electronic Check payment users have higher churn rates.

**📈 Key Insights**
Senior Citizens tend to churn more compared to others.
Month-to-month contracts are risky; customers are more likely to leave.
Customers using electronic checks are more prone to churn.
Shorter tenure customers have a significantly higher churn probability.

**💡 Recommendations**
Offer incentives for customers to switch to long-term contracts (e.g., yearly plans).
Encourage auto-payment options (like bank transfer/credit card) instead of electronic checks.
Target new customers (low tenure) with loyalty programs and better onboarding support.
Bundle additional services like tech support and security to increase customer stickiness.
