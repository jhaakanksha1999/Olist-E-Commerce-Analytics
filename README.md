Olist E-Commerce Analytics: Customer Retention & Revenue Optimization
Project Overview

This project analyzes the Brazilian Olist e-commerce marketplace to uncover the operational and customer behavior factors impacting revenue, retention, and customer satisfaction.

Using SQL, Python, and Power BI, the project transforms raw transactional data into business insights that help stakeholders identify churn risks, improve delivery performance, and optimize customer retention strategies.

The final deliverable is an interactive executive dashboard designed to support data-driven business decisions.

Business Problem

E-commerce businesses often struggle to answer critical questions such as:

Why are customers churning?
How do delivery delays affect customer satisfaction?
Which customer segments generate the most value?
Which product categories and regions drive revenue growth?
Where are operational inefficiencies occurring in the order lifecycle?

Without visibility into these metrics, businesses risk:

Losing repeat customers
Declining customer satisfaction
Revenue leakage
Inefficient logistics and marketing decisions

This project was built to solve those problems using analytics and business intelligence.

Project Goals

The primary objectives of this analysis were to:

Analyze customer purchasing behavior
Identify churn-risk customers using RFM segmentation
Measure the relationship between delivery speed and review scores
Monitor revenue and order trends over time
Evaluate operational performance across the order funnel
Build an interactive dashboard for business stakeholders
Solution Approach
1. Data Cleaning & Preparation (Python)

The raw dataset contained:

Missing values
Duplicate records
Inconsistent datetime formats
Null review scores
Multiple transaction-level tables
Key Preparation Steps
Cleaned and standardized data
Engineered delivery and churn metrics
Calculated fulfillment time
Created analytical features for segmentation and KPI tracking
Features Created
Delivery delay
Delivery buckets
Recency, Frequency, Monetary (RFM) metrics
Revenue at risk
Customer churn indicators
2. SQL Exploratory Data Analysis

SQL was used to answer business-critical questions and create reusable analytical views for Power BI.

Analysis Performed
Revenue Analysis
Total revenue
Average order value (AOV)
Monthly sales trends
Revenue by product category
Revenue by state and city
Customer Analysis
Repeat purchase behavior
Customer order frequency
Customer lifetime spending patterns
RFM Segmentation

Customers were segmented into:

Loyal
At Risk
New
Other
Churn Analysis

Customers inactive for more than 180 days were classified as churned to estimate revenue exposure and retention opportunities.

Funnel Analysis

Tracked customer progression through:

Order placed
Approved orders
Delivered orders
Reviewed orders
Delivery Performance Analysis

Measured how fulfillment speed impacts customer satisfaction and review scores.

3. Statistical Analysis & A/B Testing (Python)

Hypothesis testing was performed to validate business assumptions.

Example Tests
Fast delivery vs slow delivery customer reviews
Behavioral differences across customer segments
Techniques Used
T-tests
Confidence interval analysis
Distribution comparison

This helped move recommendations beyond assumptions into statistically supported insights.

4. Executive Dashboard (Power BI)

An interactive dashboard was developed to help stakeholders monitor KPIs and identify actionable insights quickly.

Dashboard Features
KPI Cards
Total Revenue
Total Orders
Total Customers
Revenue at Risk
Average Review Score
Interactive Visuals
Sales trend analysis
Churn trends
RFM customer segmentation
Delivery delay vs review score
Regional sales distribution
Top-selling categories
Filters
Year
Product category
Customer state
Key Business Insights
Delivery Speed Strongly Impacts Satisfaction

Customers receiving faster deliveries gave significantly higher review scores than customers with delayed deliveries.

Business Impact

Improving logistics performance can directly improve customer satisfaction and retention.

Revenue Is Concentrated Among Repeat Customers

A relatively small segment of repeat customers contributed a significant share of total revenue.

Business Impact

Retention campaigns may generate higher ROI than focusing only on new customer acquisition.

High Churn Risk Represents Revenue Exposure

A substantial number of customers became inactive after long purchase gaps, creating millions in revenue at risk.

Business Impact

Win-back campaigns targeting churn-risk customers could recover lost revenue.

Southeast Brazil Dominates Sales

States such as São Paulo and Rio de Janeiro generated the highest order volumes and revenue.

Business Impact

Regional expansion strategies can focus on underperforming markets while strengthening high-performing regions.
