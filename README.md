
# 📊 Bank Churn Analysis Dashboard

### 📁 Project Title: **Bank Customer Churn Analysis using Power BI**


## 🎯 1. Purpose of the Dashboard

This interactive Power BI dashboard is designed to analyze customer churn behavior for a bank, identifying patterns and insights from customer demographic and financial data. The core objective is to understand **why customers are leaving (churn)** and how various attributes such as age, gender, credit score, balance, and product holding influence this churn.

This enables stakeholders and decision-makers to:

* Pinpoint key churn indicators.
* Identify at-risk customer segments.
* Formulate targeted retention strategies.
* Enhance customer experience and profitability.


## 💡 2. Use Case of Churn Analysis

Churn analysis is crucial for any customer-focused industry, especially **banks and financial institutions**. Losing a customer costs more than retaining one. This dashboard helps to:

* Detect high-risk customer profiles.
* Track behavior trends across different demographics.
* Evaluate effectiveness of bank products.
* Aid the customer success and marketing teams in proactive outreach.


## 📈 3. Key Visualizations Used

The dashboard includes a variety of intuitive and powerful visuals that allow users to extract actionable insights:

### ➤ **KPI Cards**

* **Number of Customers:** Total base (10K customers).
* **Customers Lost:** Total churned customers (2037).
* **Churn Rate:** Visual gauge (20.4%) with dynamic threshold for risk analysis.

### ➤ **Donut Charts**

* **Customers by Gender:** Male vs Female distribution.
* **Customers by Active Status:** Active vs Inactive accounts.
* **Customers by Credit Card Status:** Ownership of credit card.
* **Customers by Products:** Distribution across 3 product types.
* **Customers by Country:** Regional representation of customer base.

### ➤ **Clustered Column + Line Charts**

* **Customers and Churn Rate by Age Groups**
* **Customers and Churn Rate by Credit Scores**
* **Customers and Churn Rate by Account Balance**

These combo charts show the volume of customers alongside their corresponding churn rates, offering insights into which segments are most vulnerable.


## 🧮 4. Calculated Columns / Measures Used

To derive meaningful insights, several **calculated columns and measures** were created in Power BI:

| Calculated Field / Measure | Description                                                                     |
| -------------------------- | ------------------------------------------------------------------------------- |
| `Churn Rate`               | % of customers lost = (Customers Lost / Total Customers) \* 100                 |
| `Age Group`                | Custom column categorizing age into buckets: `<20`, `21–30`, `31–40`, etc.      |
| `Credit Score Range`       | Categorized credit score ranges (e.g., `<=400`, `401-500`, etc.)                |
| `Account Balance Range`    | Segmentation of customer balances (e.g., `0`, `1K–10K`, `>200K`, etc.)          |
| `Product Type`             | Grouped into Prod 1, Prod 2, and Prod 3 for simplification                      |
| `Churn Status`             | Slicer to dynamically filter visualizations based on churned or retained status |


## 🧠 Insights Derived

* **Higher churn rate** observed in age group **51–60**, indicating older customers are more likely to leave.
* **Inactive customers**, not owning credit cards or with low credit scores show **significant churn**.
* Customers with **low account balances** or **no products** are more prone to churn.
* Churn is **evenly split across genders** and countries, hinting demographic parity but suggesting product/engagement issues.


## 📌 Summary

This dashboard acts as a comprehensive analytical tool to **monitor, analyze, and strategize around customer churn** in the banking sector. By leveraging data visualizations and DAX-calculated insights, stakeholders can identify red flags and take proactive actions to **enhance retention, satisfaction, and business growth**.


> 🛠 **Tools Used**: Microsoft Power BI, DAX, Data Modeling
> 📂 **Data Source**: Arranged From different resources.


## 📷 Snpashot

Show what the dashboard looks like: - ![Alt text](https://github.com/username/repo/assets/img.png)
Example: ![Dashboard Preview].(https://github.com/GithubSameep/Bank-Customer-Churn-Analysis/blob/main/Bank%20Churn%20Dashboard.png)

