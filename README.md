# Business Banking Contact Center: Productivity & SLA Dashboard
## Project Overview
This project focuses on analyzing the operational performance and productivity of a Business Banking Contact Center. The goal was to create a management-ready dashboard that tracks how efficiently consultant teams handle client queries across multiple channels (Phone and Email)

The analysis follows the end-to-end process of:
### Data Generation: Using ChatGPT to create a realistic mock dataset of 1,000 rows
### Data Analysis: Processing and validating the data in Excel to ensure logical consistency.
### Visualization: Building an interactive Power BI dashboard to showcase key performance indicators (KPIs) and trends.

## Dataset Description
The source material consists of a mock dataset representing business banking query logs for the year 2025

Key data points include:

Channels:_Call and Email_ 

Stakeholders:_Client, Relationship Banker, and Other_

Query Categories:_Payments, Technical, Onboarding, Account Maintenance, and Digital Banking_

Status:_Resolved, Escalated, Transfer to Different Dept, and Pending_

Resolution Metrics:_Resolution time in hours and SLA compliance status_

## Key DAX Measures
The following measures were implemented to provide executive-level insights:

Total Queries: A count of all unique query entries (Total: 1,000)

Resolution Rate: The percentage of queries successfully resolved (Achieved: 0.68)

Escalation Rate: The percentage of queries requiring escalation to higher levels (Achieved: 0.15)

SLA Compliance Rate: The percentage of queries resolved within the agreed Service Level Agreement (Achieved: 0.72)

Average Resolution Time: The mean time taken to close a query (Average: 20.20 hours)

## Dashboard Features
The Power BI report is divided into several strategic sections as seen in the project screenshots:

### 1. Executive Summary
KPI Cards: High-level overview of Total Queries, Resolution Rate, Escalation Rate, SLA Compliance, and Avg Resolution Time

Filters: Interactive slicers for Date Range, Query Category, Channel, and Consultant

### 2. Operational Insights
Queries by Category: A bar chart identifying volume drivers, with Payments and Technical queries being the most frequent

Queries by Channel: A donut chart showing the split between Call (64.5%) and Email (35.5%)

Resolution Status Distribution: A breakdown of how queries are finalized

### 3. Trend & Stakeholder Analysis
Monthly Query Volume: A line chart showing volume fluctuations throughout the year, peaking in November

Monthly SLA Performance: A trend analysis of compliance versus non-compliance

Stakeholder Distribution: Visualizing which groups (Client, Relationship Banker, or Other) initiate the most queries

### 4. Consultant Performance Scorecard
A detailed table ranking consultants by their individual resolution rates, SLA compliance, and average resolution times to help management identify top performers and coaching opportunities

## Tools Used
ChatGPT:_Mock data generation and prompt engineering_

Microsoft Excel:_Initial data cleaning and structure verification._

Power BI:_Data modeling, DAX development, and dashboard design_

