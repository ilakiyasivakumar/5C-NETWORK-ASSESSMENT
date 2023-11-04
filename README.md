# 5C-NETWORK-ASSESSMENT
# Sales Data Analysis README

## Introduction

This repository contains Python code for analyzing sales data for Sapota Yield Agriculture Private Limited (SYA). The analysis addresses various questions posed by Ram, the manager, and Bharath, Ram's manager. The dataset used for this analysis is `sales_data_2.csv`.

## Analysis for Ram's Questions

### 1. 3-Day Average of Daily Gross Profit

- **Code:** [3-day-average-gross-profit.py](3-day-average-gross-profit.py)
- **Description:** This script calculates a 3-day average of daily gross profit from the sales data. It uses a rolling window to analyze short-term trends in gross profit margins.

### 2. Insights into 3-Day Trends

- **Code:** [3-day-trend-analysis.py](3-day-trend-analysis.py)
- **Description:** This script provides insights into how the 3-day average gross profit trends change over the dataset's time period. Visualization and trend analysis are performed to identify patterns.

### 3. Sales Process Optimization

- **Code:** [sales-process-optimization.py](sales-process-optimization.py)
- **Description:** This script optimizes the sales process by calculating the gross margin contribution of each vendor and customer. It helps identify whether any vendors should be fired or customers should be let go to maximize gross margins.

### 4. Percentiles for Buying and Selling Prices

- **Code:** [price-percentiles.py](price-percentiles.py)
- **Description:** This script calculates the 25th, 50th (median), and 75th percentiles for both buying and selling prices. It provides insights into price distribution.

### 5. Analysis of Price Elasticity

- **Code:** [price-elasticity-analysis.py](price-elasticity-analysis.py)
- **Description:** This script performs price elasticity analysis to measure how changes in prices impact sales. It calculates price elasticity for different price changes (e.g., ±Rs. 1).

## Analysis for Bharath's Questions

### 1. Impact of Honoring Vendor 4

- **Code:** [vendor4-impact.py](vendor4-impact.py)
- **Description:** This script calculates the impact on the optimal gross margin if Vendor 4 must be honored. It evaluates how this condition affects the overall gross margin.

### 2. Identifying a Strategic Vendor

- **Code:** [strategic-vendor.py](strategic-vendor.py)
- **Description:** This script helps identify a strategic vendor by calculating the maximum gross margin achievable by sourcing only from one vendor. It aims to maximize the gross margin.

### 3. Price Elasticity Analysis

- **Code:** [price-elasticity-analysis.py](price-elasticity-analysis.py)
- **Description:** This script performs price elasticity analysis to determine the price elasticity of Sapota for the branch. It calculates how sales respond to price changes, helping optimize pricing strategies.

## Prerequisites

- Python 3.x
- pandas, numpy, and matplotlib libraries
- Jupyter Notebook (for running the code interactively)

## How to Run

1. Clone this repository to your local machine.
2. Install the required libraries using `pip install pandas numpy matplotlib`.
3. Navigate to the folder containing the analysis scripts.
4. Run the scripts using Python (e.g., `python 3-day-average-gross-profit.py`).

Feel free to explore each script to understand the analysis in more detail.

## Author

Ilakiya S
Email: ilakiyasivakumar.21@gmail.com

For any questions or feedback, please contact Ilakiya S via email.
