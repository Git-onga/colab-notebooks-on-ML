# 🎃Pumpkin Sales in the US
---
#@ Pumpkin Market Analysis

This project analyzes the US pumpkin market data to determine the month with the cheapest pumpkin prices.

##@ Objective

The main objective is to identify the month where pumpkin prices are lowest based on historical data.

##@ Data

The analysis uses the `US-pumpkins.csv` dataset, which contains information about pumpkin sales across different cities in the United States.

##@ Methodology

1.  **Data Loading**: The data is loaded into a pandas DataFrame.
2.  **Data Preparation**:
    *   An average price is calculated from the 'Low Price' and 'High Price' columns.
    *   The month is extracted from the 'Date' column.
    *   Irrelevant columns are dropped.
    *   Data is filtered to include only pumpkins sold by the 'bushel'.
    *   Prices are normalized to represent the price per bushel to account for different package sizes (e.g., 1/2 bushel, 1 1/9 bushel).
3.  **Data Analysis**: The average price is calculated for each month.
4.  **Visualization**: A bar plot is generated to visualize the average pumpkin price per month.

##@ Findings

The bar plot shows the average pumpkin price for each month. Based on this visualization, you can identify the month with the lowest average price.

##@ How to Run the Notebook

1.  Upload the `US-pumpkins.csv` file to your Colab environment.
2.  Run the cells sequentially.

##@ Dependencies

*   pandas
*   matplotlib
