# Chemical Process Data Quality and Exploratory Analysis

## Project Overview
This project demonstrates a data analysis workflow for a hypothetical chemical production process using Python. It focuses on data quality assessment, data cleaning, descriptive statistics, and exploratory data analysis.

## Objectives
- Generate and inspect synthetic chemical process data.
- Identify missing values, duplicate records, and invalid data types.
- Clean the dataset and export the cleaned data.
- Analyze product yield distributions.
- Explore the relationship between process temperature and product yield.
- Calculate the Pearson correlation coefficient.

## Dataset Description
The dataset contains 200 synthetic batches with the following variables:

| Variable | Description |
|---|---|
| Batch_ID | Unique batch identifier |
| Temperature_C | Process temperature (°C) |
| Pressure_bar | Process pressure (bar) |
| Flow_Rate_L_min | Flow rate (L/min) |
| Reactant_Concentration_mol_L | Reactant concentration (mol/L) |
| Product_Yield_pct | Product yield (%) |

**Note:** The dataset is synthetically generated for educational purposes and does not represent real industrial measurements.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Key Findings
- Product yield values are concentrated mainly between approximately 72% and 78%.
- The scatter plot suggests a generally positive relationship between temperature and product yield, although considerable variation exists.
- Data cleaning and exploratory analysis help identify data quality issues and patterns in the dataset.

## Project Structure
- `data/` — Project data files.
- `notebooks/` — Jupyter Notebook containing the analysis.
- `README.md` — Project documentation.

## Limitations
The dataset is synthetic, so the findings should not be interpreted as validated industrial process behaviour.

## Future Improvements
- Investigate outliers and additional data quality rules.
- Analyze the effects of pressure, flow rate, and reactant concentration on product yield.
- Apply regression or machine-learning models.
- Repeat the analysis using real-world process data when available.
