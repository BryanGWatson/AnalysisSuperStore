# 📊 Superstore Sales Data Analysis

## Overview

This project is an exploratory data analysis of the **Sample Superstore** dataset, developed as part of my Big Data studies.

The goal of the project was to apply data cleaning, transformation, analysis, and visualization techniques using **R and RMarkdown**, while identifying business insights related to sales performance, profitability, geographic trends, discounts, and seasonality.

## 🎯 Business Questions

The analysis focuses on answering several business-oriented questions:

* Which product categories generate the most sales and profit?
* Which products have the highest sales?
* Which geographic markets are profitable and which generate losses?
* How do sales change over time?
* What is the relationship between discounts and profitability?
* Do high sales necessarily translate into high profits?

## 🛠️ Tools & Technologies

* **R**
* **RMarkdown**
* **Tidyverse**
* **ggplot2**
* **dplyr**
* **readxl**
* **lubridate**
* **scales**

## 🧹 Data Preparation

Before performing the analysis, the dataset was prepared by:

* Importing the original Excel dataset into R.
* Exploring the dataset structure and summary statistics.
* Removing unnecessary fields such as Row ID and Postal Code.
* Removing duplicate records.
* Converting order and shipping dates into appropriate date formats.
* Reviewing categorical variables for consistency.

## 📈 Analysis

### Sales & Profit by Category

Sales and profit were aggregated by product category to compare overall commercial performance.

The analysis showed that **Technology was the most profitable category**, demonstrating that high-level sales performance should be evaluated together with profitability.

### Top-Selling Products

Products were grouped by total sales and profit to identify the highest-performing products.

This analysis also highlighted an important distinction: **products with high sales are not necessarily the most profitable products**.

### Geographic Performance

Sales and profit were analyzed by state to identify geographic differences in performance.

Several states, including **Texas, Illinois, and Pennsylvania**, generated net losses, suggesting potential opportunities to review pricing, discounting, product mix, or other commercial strategies in these markets.

### Monthly Sales Trends

Order dates were transformed and aggregated by month to analyze sales performance over time.

The results showed that **sales tend to increase toward the end of the year**, suggesting possible seasonality or the impact of promotional campaigns.

### Discounts vs. Profit

The relationship between discount levels and profit was explored using a scatter plot and linear trend.

The analysis indicated a **negative relationship between discounts and profitability**, suggesting that higher discounts may significantly reduce profit margins.

## 💡 Key Insights

* 💻 **Technology** was the most profitable product category.
* 📍 **Texas, Illinois, and Pennsylvania** showed net losses.
* 📉 Higher **discount levels were associated with lower profitability**.
* 📅 Sales tended to increase toward the **end of the year**.
* 📦 High-selling products were **not always the most profitable**, highlighting the importance of analyzing both revenue and profit.

## 💼 Business Takeaways

Based on the exploratory analysis, a business could consider:

* Reviewing discount strategies, particularly where higher discounts are associated with reduced profitability.
* Investigating the causes of losses in underperforming states.
* Prioritizing profitability alongside sales volume when evaluating product performance.
* Preparing inventory and marketing strategies around the observed increase in year-end sales.

These findings are exploratory and would require additional analysis before making final business decisions.

## 📁 Repository Contents

* `Analisis de Datos tienda minorista.Rmd` — RMarkdown source code containing the complete analysis.
* `Analisis-de-Datos-tienda-minorista.html` — Rendered analysis and visualizations.
* `Sample - Superstore.xls` — Dataset used for the project.
* `README.md` — Project overview and key findings.

## 🚀 Skills Demonstrated

This project demonstrates practical experience with:

* Data cleaning and preparation
* Exploratory Data Analysis (EDA)
* Data transformation with `dplyr`
* Data aggregation and grouping
* Data visualization with `ggplot2`
* Time-series aggregation
* Profitability and sales analysis
* Business insight generation
* Reproducible analysis using RMarkdown

## 👤 Author

**Bryan Gutiérrez Watson**

Aspiring Junior Data Analyst with professional experience in financial services, transaction analysis, fraud investigation, data validation, and KPI-driven environments.

[LinkedIn](https://www.linkedin.com/in/bryan-gutierrez-2b495b145)
