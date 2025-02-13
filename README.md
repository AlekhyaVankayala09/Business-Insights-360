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

In this project, we adopted the Snowflake schema for data modeling, ensuring a scalable and optimized foundation for building meaningful visualizations and reports.

![Data Modelling image](https://github.com/AlekhyaVankayala09/Business-Insights-360/blob/ef8a757b51b24c2bde52040fc0dbbc63049fcef6/Data%20Modelling%20image.jpg)

## Power BI Dashboard Overview

The dashboard comprises six pages

#### Home Page: A landing page with buttons to navigate to different pages.

![image]

#### Finance Page Overview : This page is designed to streamline financial planning, improve budgeting strategies, and enhance cost control. It provides key insights, including

- Profit and Loss Overview – A detailed snapshot of financial performance.
- Best & Least Performing Products – Identify top-selling products and those needing attention.
- Customer Revenue Insights – Recognize high-value customers and opportunities for growth.

With these insights, stakeholders can make data-driven financial decisions to maximize profitability and sustain business growth.

![image]

#### Sales Page Overview : The Sales Page provides valuable insights to boost revenue and expand market presence. Key highlights include

- Customer Contribution Analysis – Understand each customer’s impact on total sales.
- Gross Margin Insights – Assess profitability and efficiency across products or services.
- Sales Trends & Patterns – Identify growth opportunities through in-depth analysis.

By leveraging these insights, decision-makers can refine strategies, strengthen customer relationships, and drive sustainable profitability.

![image]

#### Marketing Page Overview : The Marketing Page provides data-driven insights to enhance brand reach and customer engagement. Key insights include

- Profitability by Market Segment – Analyze Gross Margin % to assess the most lucrative segments.
- Net Profit Performance – Evaluate the financial impact across customer and product categories.
- Marketing Trends & Optimization – Uncover opportunities to refine campaigns and maximize ROI.
  
With these insights, stakeholders can fine-tune marketing strategies for greater impact and efficiency.

![image]

#### Supply Chain Page Overview : The Supply Chain Page helps optimize inventory, improve demand forecasting, and enhance supplier relationships. Key highlights include

- Forecast Accuracy – Measure demand prediction precision to prev
- Net Error Analysis – Identify gaps between forecasted and actual demand.
- Supply Chain Optimization – Leverage data to streamline operations and drive cost efficiency.

This page ensures smooth supply chain performance, reducing waste and enhancing cost-effectiveness.

![image]

#### Executive Page Overview : The Executive Page offers a high-level overview of business performance, empowering leadership with key insights

- Net Sales Overview – Track overall revenue trends.
- Profitability Metrics – Monitor Gross Margin % and Net Profit % to assess financial health.
- Revenue Breakdown – Analyze sales performance across different channels (Retail, Direct, Distributors).
- Top Customers & Products – Identify primary revenue drivers.
- Geographical Insights – Evaluate sub-regional performance for targeted decision-making.

This executive dashboard consolidates essential metrics, enabling informed strategic planning.

![image]


## Key Power BI Techniques Learned
Throughout this project, various Power BI techniques were applied, including:

- ✔️ Defining business objectives and key metrics before project execution.
- ✔️ Building calculated columns and creating DAX measures for insights
- ✔️ Effective data modeling for optimized report performance
- ✔️ Implementing Bookmarks and dynamic navigation with buttons
- ✔️ Preventing calculation errors using the DIVIDE function
- ✔️ Applying dynamic titles and KPI indicators
- ✔️ Conditional formatting for better data visualization
- ✔️ Data validation techniques for accuracy
- ✔️ Publishing reports to Power BI Service and setting up auto-refresh with a personal gateway
- ✔️ Developing Power BI Apps for collaboration and access management

## Tools Used
- ✅ SQL – Data extraction and transformation
- ✅ Power BI Desktop – Dashboard creation and report building
- ✅ DAX Language – Creating calculated fields and advanced analytics
- ✅ DAX Studio – Optimizing performance and reducing file size
- ✅ Project Charter – Defining objectives and structuring the project

## Key Business Terms Explored
- 📌 Gross Margin, Gross Margin %, Gross Sales, Net Sales
- 📌 Pre-Invoice & Post-Invoice Deductions, Net Invoice Sales
- 📌 Net Profit, Net Profit %, COGS (Cost of Goods Sold)
- 📌 YTD (Year to Date), YTG (Year to Go)
- 📌 Direct Sales, Retailers, Consumers, Distributors

💡 Your feedback is invaluable! Let’s keep exploring data-driven solutions together. 🚀








