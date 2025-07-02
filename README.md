# COVID-19 Data Analysis

## Overview
This project analyzes global COVID-19 data to visualize trends, compare countries, and provide actionable insights for public health policy. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and time series forecasting using Prophet and ARIMA models.

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering (rolling averages, case fatality rate, etc.)
- Time series forecasting (Prophet, ARIMA)
- Actionable insights and policy recommendations

## Dataset
- Source: [Our World in Data - COVID-19 Dataset](https://ourworldindata.org/covid-cases)
- File: `owid-covid-data.csv`

## Project Structure
- `covid.ipynb` — Main Jupyter Notebook with all analysis and modeling
- `owid-covid-data.csv` — COVID-19 dataset
- `README.md` — Project documentation

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/alphaboy017/covid19-data-analysis.git
   cd covid19-data-analysis
   ```
2. Install required Python packages:
   ```sh
   pip install -r requirements.txt
   ```
   Or, install main dependencies manually:
   ```sh
   pip install pandas numpy matplotlib seaborn prophet statsmodels scikit-learn
   ```
3. Open `covid.ipynb` in Jupyter Notebook or JupyterLab.

## Usage
- Run the notebook cells step by step to reproduce the analysis, visualizations, and forecasts.
- Modify the country selection or model parameters as needed for custom analysis.

## Results
- Visualizations of COVID-19 trends and comparisons between countries
- Forecasts of daily new cases using Prophet and ARIMA
- Actionable insights and policy recommendations for public health

## Credits
- Data: [Our World in Data](https://ourworldindata.org/covid-cases)
- Analysis & Modeling: [Your Name or Team]

## License
This project is for educational and research purposes.