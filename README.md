# Czechoslovakia Bank Financial Data Analysis

## Project Overview

This project analyzes five years of financial data provided by Czechoslovakia Bank to uncover meaningful business insights and support data-driven decision-making. The objective is to evaluate the bank's operational performance, understand customer behavior, identify financial trends, and recommend opportunities for improving profitability through new products and services.

## Dataset Description

The analysis is based on the following relational datasets:

* **Account:** Contains account-related information, including account ID, opening date, client ID, and account type.
* **Client:** Stores customer details such as client ID, date of birth, gender, and residential district.
* **District:** Includes demographic and economic information for different districts in Czechoslovakia.
* **Loan:** Provides details of loans issued by the bank, including loan ID, account ID, issue date, loan amount, and loan status.
* **Transaction:** Records customer transactions associated with each account, including transaction type, amount, balance, and transaction date.

## Business Objectives

The bank aims to gain valuable insights into its financial operations by answering key business questions, including:

* How does the customer demographic profile vary across different districts?
* How has the bank's performance changed over the years?
* Which account types are most popular, and how do they compare in terms of usage and profitability?
* Which card types are used most frequently, and how profitable is the card business?
* How is the bank's loan portfolio distributed across different loan purposes and customer segments?
* What new financial products or services could be introduced to increase customer acquisition and overall profitability?

## Project Workflow

### Step 1: Data Preparation

* Downloaded the dataset from the source.
* Performed initial data cleaning in Microsoft Excel by removing unnecessary columns, handling inconsistencies, extracting date components, and converting dates into a standardized format.

### Step 2: Data Transformation

* Imported the cleaned data into a MySQL database.
* Created relational tables and established relationships using foreign key constraints.
* Applied data transformation techniques, including:

  * Creating derived columns
  * Standardizing data values
  * Handling missing values
  * Writing SQL queries using JOINs, CASE statements, and aggregate functions
  * Building KPI tables for business analysis

### Step 3: Data Analysis & Visualization

* Connected Power BI Desktop to the MySQL database.
* Performed exploratory data analysis (EDA) to identify trends, patterns, and business opportunities.
* Designed interactive dashboards covering:

  * Customer Demographics
  * Account Performance
  * Loan Portfolio Analysis
  * Financial KPIs
* Utilized various visualizations such as bar charts, doughnut charts, ribbon charts, cards, and slicers to create an interactive reporting experience.
* Provided data-driven recommendations to improve operational efficiency and increase profitability.

## Conclusion

The project demonstrates an end-to-end data analytics workflow, from data cleaning and transformation to visualization and business intelligence. The insights generated help Czechoslovakia Bank better understand customer behavior, evaluate financial performance, assess lending activities, and identify opportunities for strategic growth and enhanced profitability.
