# Automated Exploratory Data Analysis (EDA)

This repository contains a Jupyter Notebook for performing an Exploratory Data Analysis (EDA) on the `data.csv` file.

## Automation

This project uses GitHub Actions to automate the analysis. On every push to the `main` branch, the following steps are executed:
1.  A virtual environment is set up and the required Python packages are installed.
2.  The `eda.ipynb` Jupyter Notebook is executed from top to bottom.
3.  The updated notebook, now containing all the outputs, tables, and visualizations from the latest run, is automatically committed back to the repository.

This ensures that the EDA report is always in sync with the latest data.
