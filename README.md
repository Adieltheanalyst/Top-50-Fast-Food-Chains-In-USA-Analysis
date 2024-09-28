# Top 50 Fast-Food Chains Analysis

This repository contains an analysis of the Top 50 Fast-Food Chains in the USA, focusing on their performance metrics and trends during the pandemic period from 2020 to 2021.

## Table of Contents
- [Dataset Description](#dataset-description)
- [Objectives](#objectives)
- [Data Analysis](#data-analysis)
- [Machine Learning](#machine-learning)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Dataset Description
The dataset includes the following columns:
- **Fast-Food Chains**: Name of the chain.
- **U.S. Systemwide Sales (Millions - U.S Dollars)**: Total sales in millions.
- **Average Sales per Unit (Thousands - U.S Dollars)**: Average sales for each outlet.
- **Franchised Stores**: Number of franchised stores.
- **Company Stores**: Number of company-owned stores.
- **2021 Total Units**: Total number of stores in 2021.
- **Total Change in Units from 2020**: Change in total units from 2020 to 2021.
- **Log Sales**: Logarithmic transformation of sales.
- **Log Average Sales per Unit**: Logarithmic transformation of average sales per unit.
- **Growth Rate**: Percentage growth in sales.

## Objectives
- Analyze the impact of the pandemic on fast-food chains.
- Compare sales performance and efficiency among chains.
- Predict systemwide sales using regression analysis.
- Classify chains into performance categories using classification models.

## Data Analysis
- **Sales Analysis**: Compared total systemwide sales and average sales per unit across chains.
- **Sales Efficiency Analysis**: Evaluated the ratio of sales to total units, highlighting operational efficiency.
- **Logarithmic Analysis**: Assessed relationships using log-transformed data to reduce skewness and improve linearity.

## Machine Learning
### Regression Analysis
- Developed a regression model to predict systemwide sales based on features like average sales per unit and store counts.
- Model Performance:
  - R² Score: 0.62
  - RMSE: 0.57

### Classification Model
- Categorized chains into High, Medium, and Low performers using a Decision Tree classifier.
- Model Accuracy: 0.87

## Results
- Insights indicate that chains like Chick-fil-A excel in operational efficiency despite lower total sales compared to McDonald's, which has a larger store count. This suggests varying strategies for success within the fast-food industry.
