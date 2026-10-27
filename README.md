# COVID-19 Data Analysis

**How COVID-19 spread across countries in 2020, shown through interactive charts and animated maps.**

This notebook explores three public COVID-19 datasets with pandas and Plotly. It compares countries and continents by cases, deaths and testing, follows the US outbreak day by day, and animates the global spread on world maps.

## What the notebook covers

- **Country comparison:** bar and bubble charts of the 15 hardest-hit countries by total cases, deaths and tests, and cases against deaths on log scales.
- **Continents:** cases and testing grouped by continent.
- **US over time:** daily confirmed cases, new cases, deaths and recoveries.
- **World maps:** animated choropleth maps of confirmed cases, deaths and recoveries, day by day from 22 January 2020.
- **Causes of death:** word clouds of the conditions listed alongside COVID-19 deaths in US data.

## Data

| File | What it contains |
|---|---|
| `covid.csv` | One row per country (209 countries): population, total cases, deaths, recoveries, tests, and per-million rates, from mid-2020 |
| `covid_grouped.csv` | Daily counts per country from 22 January 2020 (35,156 rows) |
| `coviddeath.csv` | US deaths by condition and age group, February to August 2020 (12,260 rows) |

## Run it

1. Open `Covid19 Main Code.ipynb` in Jupyter or Google Colab.
2. The notebook reads the CSV files from a local Windows folder. Change each `pd.read_csv(...)` path to the file name in this repo, for example `pd.read_csv("covid.csv")`.
3. Install the libraries: `pandas`, `plotly`, `matplotlib` and `wordcloud`.

The Plotly charts are interactive, so they appear when you run the notebook. GitHub's file preview does not show them.
