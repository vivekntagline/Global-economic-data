# Global Economic Data Dashboard

![pexels-gabby-k-7412089](https://github.com/user-attachments/assets/ec3d1595-face-4e40-98f9-baf1ff87cbd2)

## Overview
This project is an **interactive and animated dashboard** visualizing various global economic indicators using data from different countries. The dashboard provides insights into:

- Top 10 Countries with Highest GDP per Capita (2023)
- Top 20 Countries with Highest Percentage of Government Expenditure (from GDP)
- Consumer Price Index across countries
- Top 10 Countries with Highest Customer Expenditure (2023)

## Features
- Animated transitions for year-wise data.
- Interactive filters to select different time periods and regions.
- Various visualization types including bar charts, box plots, treemaps, and pie charts.
- Built with **Tableau**.

## Data Sources
The visualizations are based on the following datasets:

| Dataset               | Description                     |
|---------------------|--------------------------------|
| `gdp.csv`           | GDP per capita by country and year |
| `govt_spending.csv` | Government expenditure as % of GDP |
| `consumer_price.csv` | Consumer Price Index by country and year |
| `expense-gdp.csv`    | Customer expenditure by country and year |

## EDA Pipeline
The **EDA pipeline** (Extract, Transform, Load) is implemented using Python in the `EDA.ipynb` notebook.

### Steps:
1. **Extract** data from CSV files.
2. **Transform** data by cleaning missing values and merging datasets.
3. **Load** the processed data into the visualization tool.

## Installation
To run the EDA pipeline:

```bash
# Clone the repository
git clone https://github.com/vivekntagline/global-economic-dashboard.git
cd global-economic-dashboard

# Install dependencies
pip install pandas

# Run EDA
jupyter notebook eda.ipynb
```

## Visualizations
The dashboard is built using **Tableau** and can be accessed [here](https://public.tableau.com/app/profile/vivek.nakrani/viz/GlobalEconomicData_17410875190210/Dashboard). 

## Contributing
Feel free to fork the repository and raise PRs for improvements or new visualizations.
