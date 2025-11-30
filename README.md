# Ev-charging-stations-network-analysis
The aim of the project  analyse of EV charging station infrastructure.  Includes station locations, operator performance, connector types,  installation trends, and operational status across  countries.

##  Project Overview

Data-driven insights into the EV charging ecosystem, focusing on infrastructure development, operator reliability, and strategic expansion opportunities. The countries and major charging network operators.

##  Installation & Usage
#### Prerequisites
install pandas matplotlib seaborn numpy

### Basic Analysis 

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns
#### Load dataset
df = pd.read_csv('ev_charging_stations.csv')
#### Basic overview
print(f"Total stations: {len(df)}")

print(f"Countries covered: {df['country'].nunique()}")

print(f"Operators: {df['operator'].nunique()}")

## Project Structure
ev-charging-network-analysis/

├── Problem definition & data loading/

│   ├── 01_data_cleaning.ipynb  

│   ├── 02_univariate_analysis.ipynb

│   ├── 03_bivariate_analysis.ipynb  

│   └── 04_multivariate_analysis.ipynb

├── visualizations/             

├── documentation/                    

└── README.md

## Technologies Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebooks for interactive analysis
- Data Visualization for insights communication
- Statistical Analysis for pattern recognition

## Author
- GitHub: [@theshibili](https://github.com/theshibili)
- Project Repository: [ev-charging-stations-network-analysis](https://github.com/theshibili/ev-charging-stations-network-analysis)
