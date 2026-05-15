# Casting-Defect-Analysis-dashboard
Reduction of Casting Defects in Automobile Components using Python and Power BI



Overview

This project focuses on analyzing automobile foundry production defects using Python (Pandas) for data cleaning and Power BI for interactive dashboard visualization.

The goal of this project is to identify defect patterns, monitor production quality, and improve manufacturing decision-making through data analysis.




Tools & Technologies Used
Python
Pandas
NumPy
Power BI
Git & GitHub
Project Workflow




1. Data Collection

Collected raw foundry production data containing:

Production quantity
Rejected quantity
Machine details
Temperature readings
Defect types
Shift information




2. Data Cleaning using Pandas

Performed multiple data cleaning operations such as:

Handling missing values
Removing duplicate records
Correcting invalid temperature values
Fixing negative production/rejection values
Standardizing machine names
Formatting date columns

Example:

df["Temperature"] = df["Temperature"].fillna(df["Temperature"].mean())





3. Data Visualization in Power BI

Created an interactive dashboard with:

KPI Cards
Defect Analysis
Machine-wise Rejection
Shift-wise Production
Temperature Analysis
Slicers & Filters
Trend Charts



Dashboard Insights
Identified machines with highest rejection rate
Analyzed defect distribution across components
Compared production efficiency by shifts
Monitored temperature impact on defects













