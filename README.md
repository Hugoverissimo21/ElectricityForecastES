# Modeling and Forecasting Monthly Electricity Consumption in Spain

- [Analysis & Models](https://hugoverissimo21.github.io/ElectricityForecastES/analysis.html)

- [Report](https://hugoverissimo21.github.io/ElectricityForecastES/report/ST01.pdf)

- [Slides](https://hugoverissimo21.github.io/ElectricityForecastES/slides.pdf)

## Abstract

This study analyzes and forecasts the monthly electricity consumption in Spain based on Eurostat data (2008–2025). Various statistical time series models were compared, including SARIMA, GARCH, ETS, and STLM. The SARIMA and STLM models showed good predictive performance, with STLM standing out for generating more regular residuals and narrower forecast intervals while maintaining coverage. This model was therefore selected as the best option for forecasting.

## Project Structure

- `assets/`: Contains images and other assets used in the report and slides.

- `report/`: Contains the latex source files for the report, including the main document and any supplementary materials.

- `analysis.Rmd` and `analysis.html`: The R Markdown file and its rendered HTML output containing the analysis of the data, model fitting, and evaluation.

- `raw_data.xlsx` and `data.xlsx`: The raw Eurostat data and the processed data used for analysis.

- `slides.pptx` and `slides.pdf`: The presentation slides summarizing the analysis and findings.

Extra files: `README.md` (this file), `assets.pdf` (outputs for the report and slides), `results.csv` (results of a SARIMA model selection).