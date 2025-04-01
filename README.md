# Canada_Energy_Project
CS2545 Term Project, Based on Canada Energy Data

## Objective
The Energy Data theme has been selected for this project. The objective is to analyze renewable energy usage in Canada and compare it with fossil fuel-based power generation. As global efforts focus on sustainability, Canada has experienced a shift towards green energy production. This analysis will examine the growth and distribution of renewable energy across different provinces over the past 30 years, exploring how geography, climate, and policy decisions have influenced and continue to determine energy production and consumption habits.
## Authors

- [Will Ross](https://www.github.com/wross9959)
- [Alexander Cameron](https://github.com/s0rryFSU)



## Project Structure

``` python
/cs2545_energy_project/
│
├── data/                           # Data Sets
│   ├── energy_production.csv
│   ├── population.csv
│   ├── energy_prices.csv
│   ├── climate_data.csv
│   └── energy_trade.csv
│
├── notebooks/                      # Jupyter Notebooks
│   └── energy_analysis.ipynb  
│  
├── docs/                      
│   ├── charts/
│   │   └── ...
│   ├── Project proposal.doc        # Project proposal word doc
│   └── Project Report.doc          # Final Report
│
├── .env                      
├── .gitignore
└── README.md


```
## Issues & Problems

### Issue 1: Regional Differences in Energy Production
Energy production sources vary significantly across Canada’s provinces. For example, Prince Edward Island generates 99% of its energy from wind power, whereas Alberta remains heavily reliant on fossil fuels. These regional disparities contribute to differences in cost, efficiency, and sustainability.

**Key Questions to Address:**
- Which provinces produce the most renewable energy per capita?
- How do climate and geography impact energy production?
- To what extent do provinces maximize their geographical potential for renewable energy?

### Issue 2: Lack of a National Energy Integration Strategy
Energy production in Canada is primarily managed at the provincial level, with each province generating energy for its own consumption rather than contributing to a national grid. This decentralized approach raises concerns regarding efficiency and economic potential.

**Key Questions to Address:**
- Which provinces generate the most cost-effective and efficient power?
- What are the most favorable geographical locations for renewable energy production?
- Which renewable energy sources have demonstrated the greatest effectiveness for Canada?
- How much surplus energy is wasted or could be sold to the U.S. or other provinces?

## Methodology

### Data Collection and Sources
Energy production and consumption data will be collected from publicly available datasets, including:
- Canada’s Open Data Portal: [Open.canada.ca](https://open.canada.ca/)
- Provincial Open Data Sources: as provided in the requirements
- Statistics Canada Energy Reports
- Independent Renewable Energy Studies if necessary

### Anticipated Data Processing & Analysis Approach
- Energy data will be normalized by province and per capita consumption to ensure fair comparison.
- Jupyter Notebook will be utilized for data processing, employing Pandas, NumPy, and Matplotlib.
- Renewable and fossil fuel energy distribution across provinces will be compared.
- Correlations between energy costs, production types, and geographical factors will be identified.
