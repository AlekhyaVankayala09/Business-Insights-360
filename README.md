# AtliQ Hardware - Business Insights 360


## Table of Contents

1. [Project Overview](#project-overview)
2. [Datasets](#datasets)
3. [Power BI Dashboard Overview](#power-bi-dashboard-overview)
4. [Power BI Techniques Learned](#power-bi-techniques-learned)
5. [Tools Used](#tools-used)
6. [Business Terms Learned](#business-terms-learned)

## Project Overview

AltiQ Hardware, a rapidly expanding global company, specializes in selling computers and accessories through retailers, direct sales, and distributors. With its growing presence, the company sought to enhance its decision-making process by leveraging data-driven insights.

To stay ahead in a competitive market, AltiQ Hardware adopted Power BI to transform raw data into meaningful business intelligence. This initiative empowered stakeholders across various departments—finance, sales, marketing, and supply chain—to make informed strategic decisions.

As part of this transformation, I applied my skills from the Codebasics Power BI Course to design impactful dashboards and reports, enabling the company to optimize operations and drive growth.

Link for the Business Insights 360 Dashboard - [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZGJiNDcxNWYtYjE2MC00ZTE0LWI1YWUtNDgzMGY2ZDFiZGIxIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

## Datasets

Before diving into analysis, understanding the datasets is crucial. The datasets consist of two tables:

Dimension table: Static data like customer and product details.

Fact table: Transaction data.

gdb041:


- dim_customer
- dim_market
- dim_product
- fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
- fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:

- freight_cost
- gross_price
- manufacturing_cost
- Pre_invoice_dedutions
- Post_invoice_deductions


## The Role of Data Modeling in Effective Analytics
In this project, data was extracted from MySQL and imported into Power BI, where it underwent cleaning, transformation, and structuring into a well-defined data model. But why is data modeling so crucial for analytics?

A data analyst’s workflow typically follows these four key stages:

✅ Data Extraction → ✅ Data Cleaning → ✅ Data Modeling → ✅ Data Analysis

Among these, Data Modeling plays a pivotal role in bridging raw data with meaningful insights. A well-structured data model ensures accuracy, efficiency, and seamless report performance, enabling smooth interactivity and reliable decision-making. Conversely, poor modeling can lead to slow reports, inaccurate insights, and performance issues.

By implementing a robust data model, this project maximized the potential of Power BI, ensuring data-driven decision-making across all business functions.
