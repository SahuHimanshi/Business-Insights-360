# Business Insights 360

## Project Overview

AtliQ Hardware has experienced rapid growth in recent years and is now taking a significant step forward by integrating data analytics with Power BI. This marks their first venture into leveraging data-driven insights to outpace competitors and make informed decisions. The project aims to address stakeholders key questions across various domains including finance, sales, marketing, and supply chain.


[Live Dashboard Link](https://app.powerbi.com/links/NnR4BnD14G?ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&pbi_source=linkShare)

## Tech stacks

- SQL
- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)



## Business related terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGC - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## Company’s back ground

AtliQ Hardware has established its presence globally by selling computers and computer accessories through three primary channels:

- Retailers
- Direct Sales
- Distributors

Following an underwhelming performance in the US market—primarily based on earlier survey insights and basic Excel analyses—the company is shifting to a data-driven approach. This strategic pivot is in response to competitors who have been leveraging robust analytical capabilities, making the adoption of an internal analytics team imperative.



### Dataset **Understanding.**

This initiative leverages data from two core databases, containing both static dimension data and dynamic fact data.

** Database: gdb041
- dim_customer

27 distinct markets (e.g., India, USA, Spain)

75 customers across markets

2 platforms: Brick & Mortar (physical stores) and E-commerce (online stores such as Amazon, Flipkart)

3 sales channels: Retailer, Direct, and Distributors

- dim_market

27 markets

7 sub-zones

4 regions (APAC, EU, LATAM, and NA)

- dim_product

Divisions: P & A (Peripherals, Accessories), PC (Notebook, Desktop), N & S (Networking, Storage)

14 product categories with multiple variants

- fact_forecast_monthly

Forecast data per customer on a monthly basis

Dates are standardized to the first day of each month

- fact_sales_monthly

Actual sales data structured similarly to the forecast table

** Database: gdb056
  
- freight_cost

Transportation and related costs by market and fiscal year

- gross_price

Gross pricing details by product code

- manufacturing_cost

Annual manufacturing cost per product code

- pre_invoice_deductions

Annual pre-invoice deduction percentages per customer

- post_invoice_deductions

Details of post-invoice and other deductions

## Importing data into PowerBi

- As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential

## Data Model

- Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
- Poor data modeling affects the over all performance of the report.
- In this project, we have followed Snowfall data modeling method.

![Data models](https://github.com/user-attachments/assets/f8f69579-290e-455d-8052-7f101f3f7f5b)

### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

## Home view

In Home view, all the views button will be available. User will land on specific view page by clicking the button 

- Info
- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View
- Products
- Support

![Home](https://github.com/user-attachments/assets/511e981c-b652-4ebe-b44b-ced958d5c9af)

## Finance View

![Finace](https://github.com/user-attachments/assets/7818be45-62dd-46dc-92d4-02345a984ce2)

## Sales View

![Sales](https://github.com/user-attachments/assets/0359aaea-b35e-4592-a136-1f13009f1864)

## Marketing View

![Marketing](https://github.com/user-attachments/assets/ac56654a-3c35-4926-9162-70bacc5084b2)

## Supply chain View

![Supply chain](https://github.com/user-attachments/assets/af818252-f094-45c3-bd79-4df3c8926ce5)

## Executive View

![Executive](https://github.com/user-attachments/assets/04632707-2733-4de5-9e84-dd33fd5ad7a8)


you can find the full report file here : [Report](https://app.powerbi.com/links/NnR4BnD14G?ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&pbi_source=linkShare)


## Project Outcome

By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.# Business Insights 360

