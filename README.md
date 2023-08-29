
Using-RFM-Model-for-Customer-Segmentation
 The objective of this project is to conduct a Customer Segmentation Analysis. We perform customer segmentation by utilizing the RFM Model, which stands for Recency, Frequency and Monetary analysis. This approach allows us to group customers based on their purchase transactions. For this analysis we divided the customer segment into 11 groups. The outcome of this analysis will assist in identifying the customer segments that should be targeted to boost sales revenue, for the company. To facilitate this process we developed a Sales Dashboard using Tableau and conducted data quality assessment and analysis using Python.

TABLEAU DASHBOARD 

https://public.tableau.com/views/CustomerSegmentationDashboard_16932903849940/RFMDashboard?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link


https://public.tableau.com/views/CustomerSegmentationDashboard_16932903849940/CustomerDetailDashboard?:language=en-GB&:retry=yes&publish=yes&:display_count=n&:origin=viz_share_link

FLOW:

 1. Introduction

Welcome to the README for our Automobile Business Data Analysis project. In this project, we delve into various stages of data analysis to gain insights into our customer base and their purchasing behaviors. The process involves data preparation, quality assessment, exploratory data analysis, and customer segmentation using the RFM (Recency, Frequency, Monetary) analysis approach.

 2. Data Preparation, Quality Assessment, and Cleaning

In the initial step, our data analysis journey begins with data preparation, quality assessment, and cleaning. We work with multiple datasets:

 CustomerDemographics.xlsx: Identified and resolved issues such as irrelevant columns, missing values, and data standardization. Created new features like 'Age' and 'Age Group'.

  NewCustomerList.xlsx: Addressed similar issues as above, transformed 'Date of Birth' into 'Age', and checked for data inconsistency.

  Transaction_data.xlsx: Converted 'product_first_sold_date' to datetime format, handled missing values, and created a 'Profit' feature. 

  CustomerAddress.xlsx: Standardized state data and resolved discrepancies between customer IDs.

3. Exploratory Data Analysis (EDA) on Customer Segments

After the data cleaning phase, we conducted exploratory data analysis to unearth valuable insights about customer segments:

- Analyzed age distribution for new and old customers, highlighting the popularity among the 40-49 age group.
- Explored gender-based trends in bike purchases over the last 3 years, noting higher female participation.
- Examined job industry distribution, with manufacturing and financial services sectors having the most customers.


4. RFM Analysis and Customer Segmentation

We employed an RFM (Recency, Frequency, Monetary) analysis to segment customers based on their purchasing behavior. This resulted in the identification of 11 customer segments, including Platinum Customers, Very Loyal Customers, and more.

The current distribution of customer segments reflects the state of our automobile business, enabling targeted strategies.
5. Datasets Used

The following datasets were used for our analysis:
Raw_data.xlsx:** A comprehensive dataset containing transaction data, customer demographics, and addresses.
Transactions_data.xlsx: Transaction details of customers from different Australian states.
NewCustomerList.xlsx: Information about recently acquired customers.
CustomerDemographic.xlsx: Comprehensive details about customer demographics.
CustomerAddress.xlsx: Customer address data for effective segmentation.
  
