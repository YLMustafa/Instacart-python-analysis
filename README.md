# Instacart-python-analysis

##  Project Description
This project is part of Achievement 4 in the CareerFoundry Data Analytics programme. As an analyst for Instacart, an online grocery delivery platform, the goal of this analysis is to uncover meaningful insights into customer purchasing patterns to inform a targeted marketing strategy. Instacart already enjoys strong sales but wants to dig deeper into their data to improve customer segmentation and increase marketing effectiveness.

The project involves cleaning, merging, transforming, and analysing data from multiple sources using Python and Jupyter Notebooks. The analysis is guided by stakeholder questions about customer behaviour, product demand, and order timing.

# Objective
To perform exploratory data analysis (EDA) and develop actionable insights for marketing and sales teams. The analysis supports a more personalised marketing approach by:
Identifying high-value customers
Determining peak ordering times
Understanding product demand by department
Analysing spending habits across demographic groups
Creating customer profiles and segments based on loyalty, family size, age, and region

# Repository Structure
instacart-basket-analysis-python/
│
├── /data/                 # Contains raw and cleaned datasets
│   ├── customers.csv
│   ├── orders.csv
│   ├── products.csv
│   └── merged_data.pkl
│
├── /scripts/              # Jupyter notebooks for analysis
│   ├── 01_data_import.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_exploratory_analysis.ipynb
│   └── 05_visualisations.ipynb
│
├── /exports/              # Exported subsets and flags
│   ├── loyal_customers.csv
│   ├── high_spenders.csv
│   └── family_profiles.csv
│
├── /outputs/              # Reports, visualizations, and summaries
│   ├── stakeholder_report.pdf
│   └── visualisations/
│       ├── order_timing_chart.png
│       └── department_frequency_chart.png

## Dataset Information
Sources:
**Customer Data**: A synthetic dataset provided by CareerFoundry for educational purposes.
**Instacart Dataset**:
- Name: The Instacart Online Grocery Shopping Dataset 2017
- Source: Kaggle – Instacart Market Basket Analysis
- Citation (for final report): “The Instacart Online Grocery Shopping Dataset 2017”, accessed from www.instacart.com/datasets/grocery-shopping-2017 via Kaggle.

## Technologies Used
Python 3
Jupyter Notebook
pandas, NumPy, os
matplotlib, seaborn, scipy
Anaconda (for package/environment management)

## Summary of Work Completed
- Data cleaning and transformation: handled nulls, duplicates, and data types
- Merged datasets using common identifiers
- Derived new variables: loyalty flags, price brackets, family size groups
- Performed frequency and distribution analysis
- Visualised trends in ordering behaviour
- Segmented customer base into targeted profiles
