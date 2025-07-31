# Customer-Churn-Analysis

## Objective:
To perform 'Customer Churn Analysis' and identify factors influencing customer retention and churn using:
- Demographic insights
- Contract and service usage patterns
- Revenue and customer value
- Churn risk segmentation

## Tools Used:
- **Power BI Desktop**
- **Microsoft Excel** (for cleaning & formatting)
- **Python** (for ROC/AUC model evaluation)
- **VS Code** (for Python modeling)

## Dashboard Pages Overview
#### 📍 Page 1 – Executive Summary
- Total Customers
- Churned Customers
- Churn Rate (%)
- Average Monthly Charges
- Average Customer LTV
- Churn by Gender, Contract Type, Tenure Group

#### 📍 Page 2 – Service Usage Insights
- Online Security vs Churn
- Tech Support vs Churn
- Phone Service vs Churn
- Churn by Senior Citizen, Internet Service

#### 📍 Page 3 – Revenue Trends
- Monthly Charges Distribution by Churn
- Average Customer Lifetime Value (LTV) by Churn
- Total Revenue by Churn

#### 📍 Page 4 – Risk Segmentation
- Churn Risk Flag vs Churn
- Churn by Contract Type
- Churn by Payment Method
- Churn by Contract & Payment Method (Matrix)

#### 📍 Page 5 – Interactive Exploration
- Slicers for:
  - Gender
  - Senior Citizen
  - Internet Service
  - Payment Method
  - Contract Type
  - Tenure Group
  - Churn Risk Flag
  - Monthly Charges
  - Churn
  - Customer ID
- All visuals filter dynamically

## Key Insights
#### 1. Contract Duration Impacts Churn
- Customers on month-to-month contracts have the highest churn rate, whereas 1-year and 2-year contracts show significantly lower churn, indicating that long-term commitments help reduce churn.

#### 2. Tenure is Strongly Linked to Loyalty
- Customers with less than 1 year of tenure churn the most.
- Those with 2–6 years of tenure demonstrate higher retention, showing that customer longevity builds loyalty.

#### 3. Gender Has Little Effect on Churn
- The churn rate is almost evenly distributed between male and female customers, meaning gender does not significantly influence churn behavior.

#### 4. Service Usage Affects Retention
- Lack of Online Security and no Tech Support are strong indicators of churn.
- Customers with multiple services are more likely to stay.

#### 5. Higher Paying Customers Churn More
- Customers with higher monthly charges tend to churn more, which may indicate pricing dissatisfaction or low perceived value.

#### 6. Churn Impacts Customer Lifetime Value (LTV)
- Churned users have a lower average LTV than retained users, suggesting that valuable customers are being retained better.

#### 7. Churn Risk Flag is a Reliable Metric
- The ChurnRiskFlag aligns closely with actual churn behavior, validating it as a useful predictive tool for identifying at-risk users.

#### 8. Payment Method Influences Churn
- Electronic check users churn the most, while credit card and bank transfer users show higher retention, highlighting the need to incentivize secure, auto-payment options.

## Dashboard (Screenshots)
<img width="1652" height="956" alt="Screenshot 2025-07-31 162624" src="https://github.com/user-attachments/assets/51456e0b-bb41-4a57-b359-967f902ea1df" />
<img width="1657" height="957" alt="Screenshot 2025-07-31 162648" src="https://github.com/user-attachments/assets/7bb84c67-7a9b-44af-a8bc-53c3d1beeefc" />
<img width="1653" height="951" alt="Screenshot 2025-07-31 162702" src="https://github.com/user-attachments/assets/5f2be453-c113-4d01-a5e0-1198e4d7ba89" />
<img width="1655" height="952" alt="Screenshot 2025-07-31 162718" src="https://github.com/user-attachments/assets/488a778c-c573-434c-bbd4-ea21b2fded89" />
<img width="1651" height="950" alt="Screenshot 2025-07-31 162733" src="https://github.com/user-attachments/assets/7d3341d6-ad92-4927-b9fe-254a8c903e08" />

## Files Included

- `Customer_Churn_Dashboard.pbix` – Main Power BI file
- `cleaned_churn-data.csv` – Cleaned dataset used
- `README.md` – This file
- `Images/` – Folder for screenshots

## About Me
I’m a data analyst skilled in Power BI, Excel, SQL, and Python. This is part of my end-to-end portfolio showcasing real-world business problem-solving using analytics tools.

## Connect
- [LinkedIn](https://linkedin.com/in/deepti-chaudharyy) 
