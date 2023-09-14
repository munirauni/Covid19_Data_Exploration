# COVID-19 DATA EXPLORATION

The purpose of this project is to analyze COVID-19 dataset on deaths and vaccinations. The outcome of the analysis helps us to understand following key findings:

1. Total Cases vs Total Deaths
2. Countries with highest infection rate compared to population
3. Continent with the highest death count


## DATA SOURCE: https://ourworldindata.org/covid-deaths


## DATA CLEANING & TRANSFORMATION (SQL)

The original data source in csv format was extracted using SQL for data exploration. The relevant tables needed for visualization were created using queries as follow:

[Click here for SQL Queries](https://github.com/munirauni/Covid19_Data_Exploration/blob/cd6725cc9b4ea73f4066dc36fce29eaa2269c6e7/SQL%20QUERIES%20COVID-19.sql)

The queries were then converted to excel tables and loaded into Power BI for visualization.

[Click here for the cleaned excel tables](https://drive.google.com/drive/folders/1qbuLBGgNMwLmsnLwep49uyu2q7QbnlJu?usp=sharing)


## COVID-19 ANALYSIS DASHBOARD

Below is the screenshot of finished COVID 19 DASHBOARD. PBIX file can be found [HERE](https://drive.google.com/drive/folders/1MDYeFs4bzUeLp7Aw1uH9L9Lqlif9wiOS?usp=sharing)

![](/Docs/assets/Covid-19%20Dashboard.png)


























# Sales Analysis

## Business Request 

The business request of this project is to develop a sales analysis dashboard that can be used by sales representatives and sales manager. Below are the objectives by 
both parties as well as the solution that I provided:

Role  | Objectives   |  To be developed
------------- | ------------- | ------------------
Sales Manager  | To follow better which customers and products sells the best  | Dashboard overview of internet sales which updates data once a day
Sales Manager  | To follow up the customers that purchased the most and to who we can sell more  | Dashboard that allows to filter data for each customer
Sales Representatives  | Identify best selling product  | Dashboard that allows to filter data for each product
Sales Representatives  | To identify sales overtime against budget | Dashboard with graphs and KPIs comparing against budget


## Data Cleansing & Transformation (SQL)

To create the necessary data model for analysis and fulfilling the business objectives defined above. Tables were extracted using SQL. One data source (Sales Budget) were provided in Excel format and were connected in the data model in a later step of the process.

Below are the SQL statements for cleansing and transforming the data.

[Click Here for SQL Statement](https://github.com/munirauni/Sales_Analysis/blob/0ed18e9cf7da5486b9fd7cea9eac5250bb8f4cfa/SQL%20Statement.sql)


## Data Model

The cleaned datasets were then loaded into Power BI in order to develop data model. This data model shows how FACT_Budget has been connected to FACT_InternetSales and other necessary DIM tables.

![](/docs/assets/Data%20Model%20Sales.png)


## Sales Analysis Dashboard

Below is the finished sales analysis dashboard with necessary details and visualization which help in fulfilling business objectives stated by sales manager and sales representatives.

![](/images/Sales%20Management%20Dashboard.png)

[Click Here to Access Dashboard (PBIX file)](https://drive.google.com/drive/folders/1qvx3o1HbQ9uEvH0-qA_84OCWRxiF6yvA?usp=sharing)
