# Shopify Sales Data Analysis & Demand Prediction

## Project Overview

This project analyzes Shopify-style sales data to identify sales trends, seasonal patterns, and high-demand product combinations.

The main focus is to predict which **colors and designs** are likely to have higher demand during peak and seasonal periods.

## Objective

The project aims to:

* Analyze historical sales data
* Identify popular colors and designs
* Understand seasonal sales patterns
* Find high-demand color and design combinations
* Create a demand scoring approach
* Support inventory and product planning

## Data

The actual Shopify dataset was not provided with the assignment. Therefore, a **synthetic Shopify-like dataset** is used to demonstrate the analysis.

The dataset contains information such as:

* Order ID
* Order Date
* Product ID
* Category
* Color
* Design
* Customer ID
* Quantity
* Unit Price
* Discount
* Revenue

## Analysis Process

The project follows these steps:

1. Create and prepare the sales dataset
2. Check data quality and missing values
3. Analyze overall sales performance
4. Analyze sales by color
5. Analyze sales by design
6. Analyze monthly and seasonal trends
7. Analyze color and design combinations
8. Calculate a demand score
9. Categorize products based on demand
10. Provide inventory and product planning recommendations

## Demand Prediction Approach

A demand score is calculated using:

* Historical demand – 40%
* Seasonal demand – 25%
* Recent demand trend – 20%
* Growth rate – 15%

Products are then categorized as:

* **Very High Demand**
* **High Demand**
* **Medium Demand**
* **Low Demand**

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* VS Code

## Project Structure

```text
assignment/
│
├── data/
│   └── shopify_sales_data.csv
│
├── outputs/
│   └── charts/
│
├── Shopify_Sales_Demand_Analysis.ipynb
│
└── README.md
```

## Expected Outcome

The analysis helps identify:

* High-demand colors
* High-demand designs
* Seasonal product trends
* Popular color-design combinations
* Products that may require higher inventory during peak periods

## Note

The dataset used in this project is synthetic and is intended only to demonstrate the proposed Shopify sales analysis and demand prediction approach.

