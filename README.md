# Business Insights 360

# Project Overview
AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiNWMxMDgwMDgtZDRjOC00MWE2LTk4OWItMjgyY2FmYzNlZDg0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

# Tech stacks
SQL<br>
PowerBi Desktop<br>
Excel<br>
DAX language<br>
DAX studio (for optimizing the report)<br>
Project charter file<br>

# PowerBI techniques Learnt
What are all the questions should be asked before staring the project<br>
Creating calculated columns<br>
Creating measure using DAX language<br>
Data modeling<br>
Using Bookmarks to switch between two visuals<br>
Page navigation with buttons<br>
Using divide function to prevent zero division errors<br>
Creating date table using m language<br>
Dynamic titles based on the applied filters<br>
Using KPI indicators<br>
Conditional formatting the values in visuals using icons or background color<br>
Data validation techniques<br>
PowerBi services<br>
Publishing reports to PowerBi services<br>
Setting up personal gateway to set up the auto refresh of data<br>
PowerBi App creation<br>
Collaboration, workspace, access permissions in PowerBi services<br>
And more 😅<br>
GitHub<br>

# Business related terms
Gross price<br>
Pre-invoice deductions<br>
Post-Invoice deductions<br>
Net Invoice sale<br>
Gross Margin<br>
Net sales<br>
Net profit<br>
COGC - cost of goods sold<br>
YTD - Year to Date<br>
YTG - Year to Go<br>
Direct<br>
Retailer<br>
Distributors<br>
Consumer<br>

# Company’s background
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel<br>
->Retailers<br>
->Direct<br>
->Distributors<br>

Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.

# Dataset Understanding.
Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products
dim_customer,dim_market,dim_product

Fact table : It will have the data about the transactions
fact_forecast_monthly,fact_sales_monthly
      
# Importing data into PowerBi
As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential

# Data Model
Data modeling plays a vital role and is considered as the basement of report.<br>
All the visuals will be build upon the data model.<br>
Poor data modeling affects the over all performance of the report.<br>
Following Good practices of data modeling is must.<br>
In this project, we have followed Snowfall data modeling method.

<img width="838" alt="Data_model" src="https://github.com/esther-ethel/business_insight_360/assets/49029125/a4a00340-892c-43a1-9f6c-806481f6acf5">
