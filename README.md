# Automated Exploratory Data Analysis (EDA)

This repository contains two Jupyter Notebooks for performing Exploratory Data Analysis on different datasets:

## Datasets & Notebooks

### 1. Practice Data Analysis (`eda_praxis.ipynb`)
- **Data Source**: `data.csv` - Swiss dental practice directory
- **Analysis**: Practice locations, specialties, contact information patterns
- **Visualizations**: Geographic distribution, specialty analysis, data quality metrics

### 2. Survey Data Analysis (`eda_umfrage.ipynb`)
- **Data Source**: `umfrage.xlsx` - Survey responses from dental practice staff
- **Analysis**: Professional roles, experience levels, technology usage, challenges
- **Insights**: Digital transformation needs, workflow optimization opportunities

## Automation

This project uses GitHub Actions to automate the analysis. When data files are updated on the `main` branch, the following steps are executed:

1. **Environment Setup**: Python 3.10 virtual environment with required packages
2. **Notebook Execution**: Both EDA notebooks are executed from top to bottom
3. **Auto-Commit**: Updated notebooks with all outputs, tables, and visualizations are automatically committed back to the repository

**Trigger Files**: `data.csv`, `umfrage.xlsx`, `umfrage.csv`

This ensures that both EDA reports are always in sync with the latest data.
