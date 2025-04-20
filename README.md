# Los_Angeles_Crime_Data_2020-2025
Data visualization and ETL for Power BI
ETL Pipeline
Ingest raw data into data/raw/.

Run the notebook to:

Parse dates and drop nulls.

Standardize column names.

Aggregate:

Monthly incident counts (resample('M')).

Victim demographics (age distributions, gender breakdowns).

Export cleaned CSVs into data/processed/.

Review summary tables and charts in outputs/.

Usage
Exploratory Analysis: Open and run notebooks/Los_Angeles_Crime_Data.ipynb step‑by‑step.

Power BI: Point your Power BI data source to the CSVs in data/processed/.

E.g., use Monthly_Crime_Counts.csv for time‑series visuals.

Use Victim_Age_Distribution.csv for demographic slicers.

Visualizations
We generate:

Histogram and KDE plots of victim ages.

Monthly trend lines for incident counts.

Bar charts by crime category and location.

Exported PNGs are in outputs/charts/.
