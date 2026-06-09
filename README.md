# bank-marketing-campaign-eda
Exploratory Data Analysis of a Portuguese bank's telemarketing campaign dataset
# Bank Marketing Campaign — Exploratory Data Analysis

## Overview
This project is an exploratory data analysis of a Portuguese bank's 
telemarketing campaign dataset. The goal was to understand what types 
of customers are more likely to subscribe to a term deposit, and to 
find patterns in the campaign data that could help improve marketing 
decisions.

## Dataset
- 41,188 rows, 21 columns
- Target variable: y (subscribed to term deposit — yes/no)
- No missing values

## Tools Used
- Python (Jupyter Notebook)
- pandas, numpy, matplotlib, seaborn

## Project Structure
- Data Loading and Overview
- Customer Analysis
  - Age Distribution
  - Job Type Breakdown
  - Marital Status Breakdown
- Subscription Analysis
  - Overall Subscription Rate
  - Subscription by Job Type
  - Subscription by Education Level
  - Subscription by Age Group
- Call Duration vs Subscription Outcome
- Campaign Contact Patterns
- Summary of Key Findings

## Key Findings
1. Only 11.26% of customers subscribed — showing the campaign had 
   a low overall conversion rate.
2. Students and retired customers subscribed at a higher rate compared 
   to blue-collar and service workers.
3. Customers aged 18-30 and 60+ showed proportionally higher 
   subscription rates than the middle age groups.
4. Subscribed customers had an average call duration of around 550 
   seconds, compared to 220 seconds for non-subscribers.
5. Most customers were contacted 1 to 3 times. Contacting beyond 
   5 times showed no improvement in conversion.
6. Customers with a successful previous campaign outcome were far 
   more likely to subscribe again.
