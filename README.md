# Ev-charging-stations-network-analysis
The aim of the project  analyse of EV charging station infrastructure.  Includes station locations, operator performance, connector types,  installation trends, and operational status across  countries.

##  Project Overview

Data-driven insights into the EV charging ecosystem, focusing on infrastructure development, operator reliability, and strategic expansion opportunities. The countries and major charging network operators.

##  Key Objectives

- Analyze global distribution of EV charging stations
- Evaluate operator performance and reliability metrics  
- Identify growth patterns and installation trends
- Assess connector type adoption with focus on CCS (Type 2)

##  Dataset Features

- Geographic Coverage: worldwide
- Station Attributes: Location, capacity, status, operator
- Connector Types: CCS, Type 1, Type 2, CHAdeMO, and more

##  Key Insights

#### Market Structure
- North America dominates with 60-70% of global infrastructure
- ChargePoint leads operator market with 1,750+ stations
- Circuit Électrique demonstrates highest operational reliability

#### Operational Patterns
- Multi-connector stations show 25%+ better reliability
- Seasonal peaks in Q4 (September-November)

#### Strategic Opportunities
- European growth markets (Spain, Russia, Malaysia)
- Emerging market entry in Southern Hemisphere

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
