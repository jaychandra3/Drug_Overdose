# Drug Overdose-Related Excess Mortality in the United States During the COVID-19 Pandemic (March 2020 - August 2021)

### Data holds all of the drug overdose data, demographic data, and population data

### Plots holds all of the generated plots

### main.rmd holds the main scripts, Organization of Notebook:

1. Load in Packages, Datsets, Preprocessing of Datasets
2. sARIMA Modelling Drug-Related National Level
3. sARIMA Modelling Drug-Related State Level, Correlation with COVID-19 cases
4. LOESS Approach (same organization as sARIMA section)
5. County Level Estimates- ARIMA, LOESS test (Not used in final version)
6. Regression Analysis- CCVI, SVI
7. Repeat of Original Analysis for Specific Drug Types- All Opioids, Synthetic Opioids, Cocaine, Methamphetamines, Benzodiazepines, Alcohol, Heroin
8. Additional Analyses (Age Stratification, Percent of All Deaths and All Drug Overdoses, Year vs Monthly Data Comparison)
