# Shopify-Analysis

## Problem Statement

The goal of this project is to analyze Shopify sales data in Power BI to uncover meaningful insights into transaction performance, customer purchasing behavior, and long-term customer value. By designing an interactive dashboard, the objective is to help stakeholders identify patterns in revenue generation, customer retention, and engagement trends to support data-driven decision-making.

### Steps followed 

- Step 1  : Requirement Gathering/ Business Requirements
- Step 2  : Data Walkthrough
- Step 3  : Data Connection
- Step 4  : Data Cleaning / Quality Check
- Step 5  : Data Modeling
- Step 6  : Data Processing
- Step 7  : DAX Calculations
- Step 8  : Dashboard Lay outing
- Step 9  : Charts Development and Formatting
- Step 10 : Dashboard / Report Development
- Step 11 : Insights Generation

### KPI’s Requirements

1. Transactions Performance
This section focuses on evaluating the overall health and effectiveness of sales operations by tracking:

    1.Net Sales : Total revenue generated before tax.
                      Following DAX expression was written to find Net sale:

                          Net Sales = SUM(shopify_data[Subtotal Price])
                           
   2.Total Quantity : The cumulative number of products sold.
                      Following DAX expression was written to find Net sale:

                               
                 Net Avg Order Value : The average revenue per transaction, excluding tax:
                         
   
