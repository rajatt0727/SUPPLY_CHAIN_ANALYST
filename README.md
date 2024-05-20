# Comprehensive Supply Chain Analysis Project

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Installation](#installation)
- [Data Understanding and Cleaning](#data-understanding-and-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Advanced Analysis](#advanced-analysis)
  - [Customer Segmentation](#customer-segmentation)
  - [Supplier Performance Evaluation](#supplier-performance-evaluation)
  - [Predictive Modeling](#predictive-modeling)
- [Visualization and Dashboard Creation](#visualization-and-dashboard-creation)
- [Summary of Findings](#summary-of-findings)
- [Actionable Recommendations](#actionable-recommendations)
- [Conclusion](#conclusion)

## Project Overview
This repository hosts a comprehensive supply chain analysis project using Python. The project tackles various aspects of data analysis, including data cleaning, exploratory data analysis (EDA), and advanced techniques like clustering and predictive modeling. The project also provides actionable insights based on the findings, and visualizes the data using interactive dashboards in Power BI/Tableau.

## [Datasets](https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis)
This dataset leads us with:
1. **Product Information**: SKU numbers, product categories, stock levels, lead times, order quantities, shipping times.
2. **Supplier Information**: Supplier names, locations, lead times, production volumes, shipping costs.
3. **Customer Demographics**: Gender, stock levels, order quantities, shipping times, shipping carriers.

## Installation
To replicate the analysis, follow these steps:
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/supply-chain-analysis.git
    ```
2. **Navigate into the project directory**:
    ```bash
    cd supply-chain-analysis
    ```
3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Data Understanding and Cleaning
The initial step involves loading and examining the datasets to understand their structure and the type of data they contain. This is followed by data cleaning tasks like handling missing values, removing duplicates, and ensuring proper data types.

## Exploratory Data Analysis (EDA)
Performing EDA helps in uncovering relationships, patterns, and trends through statistical summaries and visualizations. This includes box plots for stock levels by category, scatter plots for supplier performance, and bar plots for customer order quantities by gender.

## Advanced Analysis

### Customer Segmentation
Using K-Means clustering to segment customers based on their purchasing behavior.

### Supplier Performance Evaluation
Evaluating supplier performance by calculating and visualizing their efficiency.

### Predictive Modeling
Building a predictive model to estimate stock levels based on lead times, order quantities, and shipping times using linear regression.

## Visualization and Dashboard Creation
Visualizations were prepared using Power BI and Tableau to create interactive dashboards. These tools help in designing comprehensive dashboards that convey the analysis effectively.

### Power BI and Tableau:
- **Load Data** using 'Get Data' or connect to the data source.
- **Create Visualizations** such as scatter plots, bar plots, and box plots.
- **Design the Dashboard** by arranging visuals and adding slicers/filters for interactivity.

## Summary of Findings
1. **Product Analysis**: Notable variability in stock levels, significant differences in lead times and order quantities.
2. **Supplier Analysis**: Supplier 1 shows the highest efficiency.
3. **Customer Analysis**: Different purchasing behaviors identified, with males having larger average order quantities.
4. **Advanced Analysis**: Effective customer segmentation and a feasible predictive model for stock level management.

## Actionable Recommendations
1. **Inventory Management**: Optimize stock levels, focus on skincare products, and use predictive models.
2. **Supplier Optimization**: Prioritize efficient suppliers and diversify the supplier base.
3. **Customer Targeting**: Implement segment-based marketing and gender-specific strategies.
4. **Operational Improvements**: Streamline shipping processes to reduce times and enhance customer satisfaction.

## Conclusion
This project demonstrates the ability to perform advanced data analysis and derive actionable insights from supply chain data. The interactive dashboards further add to the project's comprehensiveness, making it a strong showcase of data analysis and visualization skills.

For detailed code and analysis, please refer to the Jupyter notebooks and dashboard files in this repository.
