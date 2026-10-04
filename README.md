# SBA 7(a) Small Business Lending Analysis (2022–2025)

## Overview
 
This project analyzes SBA 7(a) loan activity from 2022 through 2025 using Microsoft Excel, Power Query, Power Pivot, DAX, and the Excel Data Model.
 
The objective was to evaluate lending growth, geographic and industry concentration, charge-off risk, and employment impact using publicly available SBA loan data. The project includes data cleaning, data modeling, KPI development, dashboard creation, and business-focused analysis.
 
## Dashboard Workbook
- SBA_7A_Lending_Analysis_2022_2025.xlsx
 
## Project Screenshots
- Main Dashboard
- California Filter View
- Data Model
- DAX Measures
- Pivot Analysis

## Executive Summary

This project analyzes SBA 7(a) loan data from 2022 to 2025 using Microsoft Excel to identify lending trends, geographic and industry concentration, lending risk, and employment impact.

The analysis found that SBA lending nearly doubled during the study period, showing increased demand for small business financing. California was the largest lending market, receiving approximately $16 billion in SBA loans and accounting for 13% of total loan dollars. California, Texas, and Florida represented 26.9% of all SBA loans issued during the period.

Across industries, Full-Service Restaurants received the highest number of loans, while Hotels (except Casino Hotels) and Motels received the largest amount of funding. Although lending grew significantly, charge-off activity remained relatively low compared to total lending volume. The analysis also found that SBA-backed financing supported approximately 2.5 million reported jobs and contributed to a 66% increase in jobs supported between 2022 and 2025.

This project shows how Excel can be used to clean, prepare, analyze, and visualize large public datasets to answer business questions and support better decision-making.

---

## Business Objective

The goal of this project was to analyze publicly available SBA 7(a) loan data and identify meaningful patterns in lending activity between 2022 and 2025.

The project focused on answering these business questions:

• How did total SBA lending change between 2022 and 2025?

• Which states received the most SBA loans and how did lending activity change over time?

• Which industries received the most SBA financing?

• Where was charge-off risk highest?

• What does the Jobs Supported metric reveal about the economic impact of SBA lending?

---

## Dataset

Source: U.S. Small Business Administration (SBA) 7(a) Loan Program Data

Analysis Period:
2022–2025

The dataset contains loan-level records including:

• Loan Amount

• SBA Guaranteed Amount

• Approval Date

• Fiscal Year

• Borrower State

• Industry

• Interest Rate

• Loan Term

• Business Age

• Loan Status

• Gross Charge-Off Amount

• Jobs Supported

The analysis focused on the 2022–2025 period to provide a consistent timeframe for comparison and trend analysis.

---

## Tools Used

### Microsoft Excel

All data preparation, modeling, analysis, and dashboard development were completed in Microsoft Excel.

Key Excel features used:

• Power Query

• Power Pivot

• DAX

• Excel Data Model

• PivotTables

• PivotCharts

• Interactive Slicers

• XLOOKUP

• IF Functions

---

## Project Workflow

The project followed a structured process:

Business Question
→ Data Preparation
→ Analysis
→ Visualization
→ Insights
→ Business Interpretation

Each business question was supported by one or more KPIs to help explain not only what happened, but also why it happened.

---

## Data Preparation

The dataset was cleaned and prepared for analysis using Power Query.

### Preparation Steps

Data Review

• Reviewed dataset structure and fields

• Checked data types

• Identified missing values

• Checked for possible duplicate records

Data Cleaning

• Standardized fields and categories

• Prepared date fields

• Handled missing values

• Created lookup tables

Data Modeling

• Created the Fact Loans table

• Created the Date table

• Built relationships using the Excel Data Model

Validation

• Reviewed totals and calculations

• Tested PivotTables and dashboard filters

• Verified KPIs and visualizations

Missing categorical values were standardized as "Unknown" to preserve records and maintain reporting consistency.

---

## Data Model

A simple data model was built using Power Pivot.

### Fact Loans

The Fact Loans table contains the loan-level records used throughout the analysis.

Key fields include:

• Approval Date

• Fiscal Year

• Borrower State

• Industry

• Loan Amount

• Interest Rate

• Loan Status

• Gross Charge-Off Amount

• Jobs Supported

### Date Table

A dedicated Date table was created to support time-based analysis, trends, and year filtering.

---

## KPI Framework

Five KPIs were developed to provide a high-level view of SBA lending performance.

### Total SBA Lending

Total dollar amount of loans issued.

### Total Loans

Total number of loans issued.

### Average Loan Size

Average dollar value of loans.

### Average Interest Rate

Average interest rate across loans.

### Charge-Off Rate

Percentage of loan dollars resulting in charge-offs.

Together, these KPIs help track lending activity, loan size, borrowing costs, and risk.

---

## Dashboard

The final dashboard provides an interactive view of SBA lending activity between 2022 and 2025.

### KPI Cards

• Total SBA Lending

• Total Loans

• Average Loan Size

• Average Interest Rate

• Charge-Off Rate

### Visualizations

• SBA Lending Trend

• Top States by Lending

• Top Industries by Lending

• Charge-Off Risk Analysis

### Interactive Filters

• Fiscal Year

• State

• Industry

• Business Age

• Loan Status

The dashboard allows users to explore lending activity from a national view down to specific states, industries, business-age categories, and loan-status groups.

---

## Executive Insights

• SBA lending nearly doubled between 2022 and 2025, reflecting strong growth in small business financing.

• California, Texas, and Florida accounted for 26.9% of all SBA loans, highlighting concentrated lending activity.

• The top three industries represented only 10.4% of total loans, indicating broad participation across industries.

• Overall charge-off losses remained low relative to total lending volume despite elevated risk in select industries.

• SBA-backed lending supported approximately 2.5 million jobs, with reported employment impact increasing 66% during the period.

---

## Key Findings

### SBA Lending Growth

Total SBA lending nearly doubled between 2022 and 2025, showing strong growth in small business financing activity.

California received approximately $16 billion in SBA loans and accounted for 13% of total SBA lending.

### State Analysis

California led all states with approximately 28,900 loans and represented 11.4% of total loan volume.

California also experienced 97% growth during the analysis period.

Hawaii recorded the fastest growth rate at 110%.

California, Texas, and Florida accounted for 26.9% of all SBA loans.

### Industry Analysis

Full-Service Restaurants received the highest number of loans, with more than 12,000 loans representing 4.7% of total loan volume.

Hotels (except Casino Hotels) and Motels received the highest amount of funding at approximately $7.4 billion.

The top three industries accounted for only 10.4% of total loan volume, showing that SBA lending remained spread across many industries.

### Charge-Off Risk

Charge-off losses remained low compared to overall lending activity.

Limited-Service Restaurants recorded the highest charge-off amount at approximately $25.5 million.

California recorded the highest state-level charge-offs at approximately $86.6 million.

The Secondary Smelting and Alloying of Aluminum industry recorded the highest charge-off risk at 71.5%.

### Employment Impact

SBA-backed loans supported approximately 2.5 million reported jobs between 2022 and 2025.

Full-Service Restaurants supported more than 248,000 jobs and represented 9.6% of total jobs supported.

California supported approximately 302,000 jobs and represented 11.7% of total jobs supported.

Jobs supported increased by approximately 66% during the study period.

---

## Key Business Takeaways

• SBA lending expanded significantly between 2022 and 2025.

• Lending activity was concentrated in several major states, particularly California, Texas, and Florida.

• While some industries received a larger share of financing, SBA lending remained broadly distributed across many industries.

• Charge-off activity remained relatively low overall, though certain industries showed higher levels of risk.

• SBA-backed financing was associated with substantial employment support and workforce growth.

---

## Data Limitations

• The dataset does not contain a unique universal loan identifier.

• Jobs Supported represents reported values and should not be interpreted as permanent net job creation.

• Charge-off rates should be evaluated alongside loan volume because small segments can produce unusually high percentages.

• The analysis reflects SBA 7(a) loan activity and not the entire small-business lending market.

• Correlation does not imply causation.

• Missing categorical values were standardized as "Unknown."

---

## Skills Demonstrated

### Excel & Business Intelligence

• Microsoft Excel

• Power Query

• Power Pivot

• DAX

• Excel Data Model

• PivotTables

• PivotCharts

• Interactive Slicers

### Data Analysis

• Data Cleaning

• Data Transformation

• Data Validation

• Data Modeling

• KPI Development

• Dashboard Development

• Trend Analysis

• Industry Analysis

• Geographic Analysis

• Risk Analysis

### Communication

• Business Question Development

• Insight Generation

• Data Storytelling

• Executive Reporting

---

## Final Takeaway

This project demonstrates how Microsoft Excel can be used to turn a large public dataset into meaningful business insights.

By cleaning, modeling, and analyzing SBA 7(a) loan data, I was able to identify lending trends, evaluate risk, measure employment impact, and answer business-focused questions through an interactive dashboard.

Raw Data → Cleaning → Transformation → Data Modeling → Analysis → KPIs → Dashboard → Insights

This project highlights skills in data preparation, data analysis, dashboard development, and business communication while showing how raw data can be transformed into useful insights that support better decision-making.
