# EDA-project-on-Blinkit-sales
# 

Exploratory Data Analysis of the BlinkIT grocery dataset to understand **sales patterns, outlet performance, product mix, and data quality**.

## Overview

This project analyzes **8,523 grocery records across 12 variables**, covering item characteristics, outlet details, visibility, sales, and ratings.

The analysis focused on:

- Cleaning and standardizing categorical data
- Identifying missing values and duplicate records
- Exploring sales distribution and product categories
- Comparing sales across fat content, outlet location, and establishment year
- Examining the relationship between item visibility and sales
- Identifying high-performing products and outlets

## Key Insights

- **Sales are fairly widely distributed**, with an average of ~140.99 and a maximum of ~266.89.
- **Tier 3 outlets generate the highest total sales**, followed by Tier 2 and Tier 1.
- **Fruits and Vegetables** and **Snack Foods** have the largest product volumes and contribute substantially to overall sales.
- By total sales, **Fruits and Vegetables** and **Snack Foods** are among the strongest-performing categories, while **Seafood** and **Breakfast** have comparatively lower contributions.
- **Item Fat Content** shows relatively little difference in average sales after identifying inconsistent labels such as `LF`, `Low Fat`, `low fat`, `Regular`, and `reg`.
- **Item Weight contains 1,463 missing values**, concentrated in particular outlet records, so missingness is not random and should be handled carefully before modeling.
- **Item Visibility does not show a strong straightforward relationship with Sales**, suggesting that visibility alone is insufficient to explain sales performance.
- The highest individual sales values are concentrated around **264–267**, with several high-rated products reaching this range.


## Visual Analysis

The project uses:

- Sales distribution histogram
- Item-type volume comparison
- Item Visibility vs. Sales scatter plot
- Average Sales by Fat Content
- Sales by Outlet Establishment Year

These visualizations were used to identify distribution patterns and relationships rather than relying only on aggregate statistics.

## Tools

**Python · Pandas · Matplotlib · Jupyter Notebook**

## Dataset

BlinkIT Grocery Sales dataset containing item-level and outlet-level information.

## Project Goal
The goal of this project was to apply **Python-based data analysis techniques** to a real-world grocery dataset and turn raw data into meaningful insights.
