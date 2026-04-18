# Florida Real Estate Sales Analysis Dashboard 🏠📊
# Project Overview
This project provides a comprehensive analysis of the Florida Real Estate Market using a dataset of over 10,000+ raw records. The goal was to transform messy, web-scraped data into a high-integrity, interactive Power BI dashboard to uncover pricing trends, property distributions, and geographical hotspots across Florida.

# Key Features
Interactive Map: Visualizes property sales density and pricing across various Florida ZIP codes.

Dynamic KPIs: Real-time tracking of Total Listings, Average Sale Price, and Average Square Footage.

Property Segmentation: A breakdown of market share between Condos, Townhomes, and other property types.

Animated Market Trends: An animated scatter plot showing the correlation between property age (Year Built), size (Sqft), and final sold price.

Forecasting: Built-in predictive analysis to estimate future market values based on historical data.

# Data Processing & ETL (The Tech Stack)
A significant part of this project involved advanced Data Engineering in Power Query:

# Data Integrity:
Handled a dataset where structural shifts caused text descriptions to appear in numerical columns.

# Error Handling:
Performed rigorous cleaning, reducing the raw 10k+ noise into 900+ high-quality, verified records for accurate visualization.

# Type Conversion:
Converted raw strings into Currency, Decimal, and Postal Code formats.

# DAX Calculations:
Created custom measures for Price per Sqft and year-over-year growth metrics.

# Dashboard Preview
<img width="1439" height="807" alt="1111" src="https://github.com/user-attachments/assets/0f759524-6ffe-4f1b-8330-9c7f1361d56c" />
<img width="1438" height="807" alt="22222" src="https://github.com/user-attachments/assets/a304c9dc-cc4f-42b0-94ac-8ac0ea0fe869" />



# How to Use
Dataset: The raw CSV file is included in the /data folder.

# Power BI File:
You can download the .pbix file to explore the interactive filters and animations.

# Insights:
Use the Play Axis on the scatter chart to see how the market evolved relative to property age.

# Tools Used
Power BI Desktop (Visualization & DAX)

Power Query (ETL & Data Cleaning)

# Kaggle (Data Source)
