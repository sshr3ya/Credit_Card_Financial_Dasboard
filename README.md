 Credit Card Customer & Financial Analysis Dashboard

 # Project Overview

This project focuses on analysing credit card customer and transaction data to understand customer behaviour, financial performance, transaction patterns, and key business metrics.

The project uses PostgreSQL for data storage and processing and Microsoft Power BI for data analysis, DAX calculations, visualization, and dashboard development.

The project also demonstrates an incremental data update workflow by adding 53rd-week data to the SQL database and refreshing the Power BI dashboard.



# Project Objective

The main objective of this project is to build an interactive Power BI dashboard that helps analyze:

* Credit card revenue and interest earned
* Customer transaction behaviour
* Customer demographics
* Card category performance
* Transaction methods
* Customer satisfaction
* Delinquent accounts
* Weekly and quarterly performance
* Customer segments and their financial contribution

The dashboard is designed to provide meaningful insights that can support business and customer-related decision-making.



# Tools & Technologies

* PostgreSQL – Database creation, data storage, and data manipulation
* SQL – Data querying and analysis
* Microsoft Power BI – Dashboard development and visualization
* DAX – Calculated columns and measures
* CSV – Source datasets
* GitHub – Project documentation and version control


#  Dataset

The project uses four datasets containing credit card customer, transaction, and financial information.

### 1. Credit Card Dataset — 'creditcard'

Contains credit card-related information used to analyze customer transactions, financial performance, card usage, and other credit card metrics.

Key information includes:

* Transaction details
* Interest earned
* Annual fees
* Transaction amount and count
* Credit card category
* Customer satisfaction
* Delinquent account information
* Revolving balance
* Transaction method


### 2. Customer Dataset — 'customer'

Contains customer-level information used to analyze customer demographics and characteristics.

Key information includes:

* Customer age
* Gender
* Income
* Education level
* Marital status
* Customer job
* Number of dependents
* Geographic information
* Other customer attributes



### 3. Credit Card Additional Dataset — 'cc_add'

'cc_add' stands for Credit Card Additional Data.

This dataset contains incremental credit card data for the 53rd week (31st December).

It was used to simulate a real-world scenario where new weekly credit card data becomes available and needs to be added to the existing SQL database.

After adding the new records to the database, the Power BI dashboard was refreshed to incorporate the latest data.



### 4. Customer Additional Dataset — 'cust_add'

'cust_add' stands for Customer Additional Data.

This dataset contains additional customer records associated with the updated credit card data.

The records were added to the existing customer data in the SQL database so that the Power BI dashboard could incorporate the latest customer information.



#  Project Workflow

The project was completed through the following steps:

### Step 1 — Prepare the Data

The four CSV datasets were reviewed and prepared for database import.

### Step 2 — Create SQL Tables

Tables were created in PostgreSQL to store the customer and credit card data.

### Step 3 — Import Data into PostgreSQL

The original datasets were imported into the SQL database.

### Step 4 — Connect Power BI to SQL

The PostgreSQL database was connected to Power BI for analysis and visualization.

### Step 5 — Data Analysis & DAX

DAX was used to create calculated columns and measures for important business metrics.

Examples include:

* Revenue
* Interest Earned
* Transaction Amount
* Transaction Count
* Customer Satisfaction
* Weekly performance
* Quarterly performance

### Step 6 — Dashboard Development

Interactive dashboards were developed to analyze customer demographics, financial performance, transaction behavior, and card usage.

### Step 7 — Incremental Data Update

The 'cc_add' and 'cust_add' datasets were added to the existing SQL database to simulate the arrival of new weekly data.

The Power BI dashboard was then refreshed to reflect the updated data.



#  Dashboard 1 — Customer & Financial Analysis

The first dashboard focuses on customer demographics and financial performance.

### Key Analysis

* Revenue by Gender
* Revenue by Age Group
* Revenue by Customer Job
* Revenue by Salary Group
* Revenue by Dependent Count
* Revenue by Marital Status
* Revenue by Education Level
* Top 5 States by Revenue
* Customer Satisfaction
* Card Category


# 📊 Dashboard 2 — Transaction & Revenue Analysis

The second dashboard focuses on credit card transaction behaviour and financial performance.

### Key Analysis

* Quarterly Revenue & Transaction Count
* Revenue by Expenditure Type
* Revenue by Education Level
* Revenue by Customer Job
* Revenue by Transaction Method
* Revenue by Card Category
* Transaction Amount
* Transaction Count
* Interest Earned
* Revenue


# 📈 Key Insights

The analysis provides insights into:

* Revenue contribution across different customer segments
* Customer transaction behaviour across card categories
* Differences in revenue across demographic groups
* Transaction patterns across chip, swipe, and online methods
* Quarterly changes in revenue and transaction activity
* Customer satisfaction levels
* Delinquent versus non-delinquent customer segments
* Performance of different credit card categories
* High-performing states and customer segments


#  Business Recommendations

Based on the analysis, the following strategies can be considered:

* Focus marketing efforts on high-value customer segments.
* Develop targeted offers based on customer demographics and transaction behaviour.
* Monitor delinquent accounts to manage credit risk.
* Analyze high-performing card categories to improve product strategy.
* Encourage card usage through targeted rewards and promotional campaigns.
* Monitor customer satisfaction and identify opportunities to improve customer experience.
* Regularly update the dashboard with new data to support timely business decisions.
