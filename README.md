# Telecom Customer Churn Analysis

Power BI dashboard analyzing telecom customer churn, identifying high-risk customers, churn drivers, and revenue impact to support data-driven retention strategies.



## 📊 Telecom Customer Churn Analysis (Power BI)



## 1. Title

**Telecom Customer Churn Analysis & Prediction | Power BI Dashboard**



## 2. Executive Summary

Customer churn is a critical challenge for telecom companies, directly impacting revenue and growth.  
This project analyzes historical customer data to identify churn patterns and predict high-risk customers.  
Interactive Power BI dashboards were built to help stakeholders understand churn drivers, customer behavior, and revenue impact, enabling data-driven retention strategies.



## 3. Business Problem

Telecom companies face increasing competition and customer attrition due to pricing, service quality, and contract flexibility.

**Key business questions addressed:**

- Which customer segments are more likely to churn?
- What factors (contract type, payment method, services, tenure) influence churn?
- How does churn impact revenue?
- Which customers are at high risk of churning in the future?



## 4. Methodology

- Collected and cleaned telecom customer data  
- Performed data transformation and feature grouping (Age Group, Tenure Group, Charges Range)  
- Created calculated measures for churn rate, total churn, and revenue impact  
- Built interactive dashboards in Power BI:
  - Executive Summary for high-level insights  
  - Prediction Dashboard to identify high-risk customers  
- Applied filters and slicers for dynamic analysis by state, contract type, internet service, and payment method  



## 5. Skills

- Python  
- SQL
- MS Excel 
- Power BI  
- Data Cleaning & Transformation  
- DAX Measures  
- Data Visualization & Dashboard Design  
- Business Analytics  
- Churn Analysis  
- Customer Segmentation  



## 6. Results & Business Recommendations

### 🔍 Key Findings
- Higher churn observed among **Month-to-Month contract customers**
- Customers using **Mailed Check** and **Bank Withdrawal** payment methods show higher churn rates
- Certain age groups and states have significantly higher churn
- High-risk customers contribute substantially to potential revenue loss

### 💡 Recommendations
- Introduce long-term contract incentives to reduce churn
- Offer targeted retention plans for high-risk customer segments
- Improve service offerings for customers with higher churn probability
- Implement proactive engagement strategies for predicted churners



## 7. Next Steps

- Integrate machine learning models for advanced churn prediction
- Automate data refresh for real-time churn monitoring
- Perform cohort analysis to track churn over time
- Extend analysis to customer lifetime value (CLV)



## 8. Tools & Technologies Used

- **Microsoft Excel** – Initial data inspection and basic cleaning  
- **SSMS (SQL Server Management Studio)** – Data querying and validation  
- **Python (Jupyter Notebook)** – Data cleaning, preprocessing, and exploratory analysis  
- **Power BI** – Data modeling, DAX measures, and interactive dashboard creation  

## 📊 Dashboard Preview

### Executive Summary
![Executive Summary](Dashboard%20Preview/Executive%20Summary.png)

### Churn Prediction
![Churn Prediction](Dashboard%20Preview/Prediction%20Insights.png)


## 9. How to Run This Project

### Step 1: Data Preparation
- Load the telecom customer dataset into **Excel** for initial inspection
- Remove duplicates and handle missing values if required

### Step 2: SQL Analysis (SSMS)
- Import the dataset into **SQL Server**
- Use SQL queries to:
  - Validate data consistency
  - Analyze churn distribution
  - Perform aggregations if required

### Step 3: Python Analysis (Jupyter Notebook)
- Open the Jupyter Notebook file
- Run the notebook to:
  - Clean and preprocess the data
  - Create derived columns such as Age Group and Tenure Group
  - Perform exploratory data analysis (EDA)
- Export the cleaned dataset as a CSV file

### Alternative (Without Jupyter Notebook)
If Python is not used, data cleaning and transformations can be performed directly in:
- **Excel (Power Query)**  
OR  
- **Power BI Power Query Editor**



### Step 4: Power BI Dashboard
- Open the `.pbix` file in **Power BI Desktop**
- Load the cleaned dataset (CSV / SQL Server)
- Review data model and DAX measures
- Interact with dashboards using slicers and filters


## Conclusion

This project demonstrates an end-to-end approach to analyzing customer churn using real-world telecom data.  
The insights derived from this analysis can help businesses identify high-risk customers, understand key churn drivers, and design effective retention strategies.
