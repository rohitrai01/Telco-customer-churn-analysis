Telco Customer Churn Analysis

This project delves into the Telco Customer Churn dataset to identify the key factors that lead to customer attrition. Through a detailed exploratory data analysis (EDA), we uncover significant patterns and trends that influence a customer's decision to leave the service.

The goal of this analysis is to provide actionable insights that can help improve customer retention strategies and reduce churn rates.

📁 Project Overview

Customer churn is a critical metric for any service-based business. This analysis uses the IBM Telco Customer Churn dataset to visualize and understand the relationship between customer demographics, service usage, account details, and churn.

Key areas of exploration include:

Data Cleaning & Preprocessing: Handling missing values and ensuring data types are correct for analysis.

Univariate & Bivariate Analysis: Examining individual features like tenure, contract type, and payment method, and their relationship with churn.

Data Visualization: Creating clear and insightful visualizations using Matplotlib and Seaborn to communicate key findings.

Insight Generation: Summarizing the most important factors that appear to drive customer churn.

📊 Key Findings

The analysis reveals several critical factors associated with customer churn:

1. Contract Type is Crucial

Customers on a Month-to-month contract are significantly more likely to churn compared to those with One year or Two year contracts. This suggests that longer-term commitments foster customer loyalty.

2. Tenure is a Strong Predictor

A high churn rate is observed among customers with a very short tenure (1-2 months). Conversely, customers who have been with the company for many years are much more loyal and less likely to leave. The longer a customer stays, the more valuable they become.

3. Service Add-Ons and Internet Service Matter
   
Internet Service: Customers using Fiber optic internet have a higher churn rate than those using DSL.

Tech Support & Online Security: Customers without these additional services are far more likely to churn than those who have them. This highlights the importance of security and support features in customer retention.

4. Demographic Factors Show Nuance
   
Senior Citizens: This demographic shows a significantly higher churn rate compared to non-senior citizens, indicating a specific target group for retention efforts.

Gender: There is no significant difference in churn rates between male and female customers.

Paperless Billing: Customers using paperless billing have a higher churn rate, which could suggest a need for better communication via digital channels.

5. Payment Method is an Indicator

Customers using Electronic check have a much higher churn rate compared to those using other payment methods like Credit card, Bank transfer, or Mailed check. This might be an early warning sign or a preference that could be addressed.

🛠️ Tools & Technologies

Python 3.11.5

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib: For creating static, animated, and interactive visualizations.

Seaborn: For statistical data visualization based on Matplotlib.

📂 Dataset

The dataset, Telco-Customer-Churn-raw_data.csv, includes customer details from a telecommunications company. It contains information about:

Demographics: Gender, SeniorCitizen, Partner, Dependents.

Customer Account: Tenure, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges.

Services Subscribed: PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies.

📝 Conclusion

This analysis provides a data-driven foundation for understanding customer churn. The key takeaway is the high risk associated with:

- Short-term contracts

- Low tenure

- The absence of security and support services

- Fiber optic internet

- Electronic check payments

By focusing retention strategies on these areas, a company can effectively reduce its churn rate and build a more loyal customer base.
