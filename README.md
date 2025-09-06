# Customer\_Churn\_Analysis

Data Analytics project analyzing customer churn for actionable business insights.



\# Customer Churn Analysis: Uncovering Why Customers Leave



\## 📌 Project Overview

Customer churn is a major issue in the telecommunications industry. Retaining customers is far more cost-effective than acquiring new ones. This project analyzes customer-level data to identify patterns, drivers of churn, and actionable insights that can help the company reduce customer attrition.



---



\## 🗂 Dataset

\- Source: \[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  

\- Rows: 7,043  

\- Columns: 21  



\*\*Key Columns:\*\*

\- `CustomerID`: Unique identifier  

\- `Gender`: Male/Female  

\- `SeniorCitizen`: 0 = No, 1 = Yes  

\- `Partner`, `Dependents`: Yes/No  

\- `Tenure`: Number of months with the company  

\- `PhoneService`, `MultipleLines`, `InternetService`  

\- `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`  

\- `Contract`: Month-to-month/One year/Two year  

\- `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`  

\- `Churn`: Yes/No  



---



\## 🔧 Tools \& Technologies

\- \*\*Python\*\* (Pandas, NumPy, Matplotlib, Seaborn) → Data cleaning \& visualization  

\- \*\*SQL\*\* → KPI queries and aggregation  

\- \*\*Power BI\*\* → Interactive dashboard creation  

\- \*\*GitHub\*\* → Project hosting  



---



\## 🧹 Data Cleaning \& Preprocessing

\- Converted `TotalCharges` to numeric and filled missing values.  

\- Standardized column names for easier analysis.  

\- Converted `Yes/No` columns to binary (0/1) for analysis.  

\- Verified no missing values remain.  



---



\## 📊 Exploratory Data Analysis (EDA) Insights



\### 1️⃣ Overall Churn

\- ~26% of customers have churned.  

\- Indicates that 1 in 4 customers leave, which is significant.  



\### 2️⃣ Demographics

\- \*\*Senior Citizens\*\* churn more than younger customers.  

\- Gender has minimal impact on churn.  



\### 3️⃣ Contract \& Billing

\- Month-to-month contracts → highest churn (~45%).  

\- One-year and two-year contracts → much lower churn.  

\- Paperless billing and electronic check payments → slightly higher churn.  



\### 4️⃣ Services \& Charges

\- High monthly charges → higher churn.  

\- Customers with multiple services have lower churn.  



\### 5️⃣ Correlation Insights

\- Tenure (customer duration) → strong negative correlation with churn.  

\- Total charges → higher for retained customers.  



---



\## 💡 Business Recommendations

1\. \*\*Focus on Month-to-Month Customers\*\*: Encourage longer contracts via incentives.  

2\. \*\*Target High Monthly Charges\*\*: Offer bundled packages or loyalty discounts.  

3\. \*\*Senior Citizen Support Programs\*\*: Improve retention with dedicated services.  

4\. \*\*Early Tenure Retention\*\*: Onboard new customers effectively within first 6 months.  



---



\## 📈 Dashboard

\- Created an \*\*interactive Power BI dashboard\*\* to visualize:

&nbsp; - Churn by demographics, contract type, and payment method  

&nbsp; - Monthly charges distribution  

&nbsp; - Key KPIs and correlations  



\*(Include screenshot or link to your dashboard here)\*  



---



\## 🔗 Project Repository Structure



