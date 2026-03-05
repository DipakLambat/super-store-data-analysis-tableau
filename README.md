# Sample Super Store Dashboard (Tableau)

An interactive **Tableau dashboard** built using the **Sample Superstore
dataset** to analyze business performance across **sales, profit,
customers, products, regions, and shipping modes**.

The dashboard helps identify **high-performing products, profitable
regions, customer segments, and shipping trends** to support data-driven
business decisions.

------------------------------------------------------------------------

# Table of Contents

-   [Project Overview](#project-overview)
-   [Key Metrics](#key-metrics)
-   [Dashboard Visualizations](#dashboard-visualizations)
-   [Filters](#filters)
-   [Key Insights](#key-insights)
-   [Dataset](#dataset)
-   [Tools & Technologies](#tools--technologies)
-   [Project Structure](#project-structure)
-   [How to Open the Project](#how-to-Open-the-Projec)
-   [Future Improvements](#future-improvements)

------------------------------------------------------------------------

# Project Overview

The **Sample Super Store Dashboard** provides a complete overview of
sales and profit performance using Tableau.

The dashboard allows users to:

-   Monitor overall sales and profit
-   Identify top-performing products
-   Analyze shipping performance
-   Compare regional sales performance
-   Understand customer segments

This project demonstrates **data visualization, business analytics, and
dashboard design skills using Tableau**.

------------------------------------------------------------------------

# Key Metrics

  Metric            Value
  ----------------- -----------
  Total Sales       2,297,201
  Total Profit      286,397
  Total Customers   793
  Total Products    1,862

------------------------------------------------------------------------

# Dashboard Visualizations

## Category vs Sales

A pie chart showing sales distribution across product categories:

-   Technology
-   Furniture
-   Office Supplies

------------------------------------------------------------------------

## Top 10 Products by Profit

A horizontal bar chart displaying the **top 10 most profitable
products**.

------------------------------------------------------------------------

## Ship Mode Performance

A table showing performance by shipping type:

-   First Class
-   Same Day
-   Second Class
-   Standard Class

Metrics include:

-   Quantity
-   Sales
-   Profit
-   Discount

------------------------------------------------------------------------

## Count of Ship Mode

A bubble chart displaying the distribution of shipping methods used by
customers.

------------------------------------------------------------------------

## Profit & Sales by State

A geographic map showing sales and profit distribution across U.S.
states.

------------------------------------------------------------------------

## Segment vs Region vs Quantity

A treemap visualizing quantity purchased across different **customer
segments and regions**.

Segments:

-   Consumer
-   Corporate
-   Home Office

------------------------------------------------------------------------

## Total Sales by Region

A bar chart comparing sales performance across:

-   Central
-   East
-   South
-   West

------------------------------------------------------------------------

## Quantity vs Profit vs Sub-Category

A scatter plot analyzing the relationship between:

-   Quantity sold
-   Profit generated
-   Product sub-category

------------------------------------------------------------------------

# Filters

  Filter      Purpose
  ----------- -----------------------------
  Region      Filter by geographic region
  Category    View category performance
  Segment     Analyze customer segments
  Ship Mode   Explore shipping trends

------------------------------------------------------------------------

# Key Insights

-   Technology category generates the highest sales
-   Standard Class is the most used shipping method
-   West region shows strong sales performance
-   Some products have high quantity but low profit
-   Consumer segment has the highest order volume

------------------------------------------------------------------------

# Dataset

The project uses the **Sample Superstore dataset** containing:

-   Order ID
-   Product ID
-   Category
-   Sub‑Category
-   Sales
-   Profit
-   Quantity
-   Discount
-   Region
-   State
-   Ship Mode
-   Customer Segment

------------------------------------------------------------------------

# Tools & Technologies

-   **Tableau**
-   Excel

Visualization methods used:

-   KPI Cards
-   Pie Charts
-   Treemap
-   Scatter Plot
-   Geographic Map
-   Bar Charts
-   Bubble Charts

------------------------------------------------------------------------

# Project Structure

    Superstore-Tableau-Dashboard
    │
    ├── data
    │   └── superstore_dataset.csv
    │
    ├── dashboard
    │   └── superstore_dashboard.twbx
    │
    ├── images
    │   └── dashboard_preview.png
    │
    └── README.md

------------------------------------------------------------------------

# How to Open the Project

Follow the steps below to open and explore the Tableau dashboard.

## 1. Download the Repository

 click **Code → Download ZIP** and extract the folder.

## 2. Install Tableau

Make sure you have **Tableau Desktop** or **Tableau Public** installed on your system.

## 3. Open the Dashboard

1. Navigate to the project folder.
2. Open the file:

```
superstore_dashboard.twbx
```

3. The dashboard will open in Tableau.

## 4. Explore the Dashboard

Use the interactive filters to analyze the data:

* Region
* Category
* Segment
* Ship Mode

These filters allow dynamic exploration of sales, profit, and customer trends.

------------------------------------------------------------------------

# Future Improvements

-   Sales forecasting
-   Customer segmentation analysis
-   Profit optimization analysis
-   Integration with live data

------------------------------------------------------------------------
