# Renewable Energy Analytics

A compact data-analytics case study on Germany's electricity generation from 2018–2023 — renewable-energy growth, photovoltaic expansion, weather correlations, and short-term solar-generation forecasting.

This is the cleaned portfolio version of an original university project. The repo intentionally keeps the analytical artifact instead of dumping the full course archive.

## Core question

How did Germany's electricity mix change from 2018 to 2023, and how do weather patterns and photovoltaic expansion relate to solar electricity generation?

## Main artifact

```text
notebooks/renewable_energy_analytics.ipynb
```

The notebook contains the full workflow:

```text
data preparation
→ data quality checks
→ exploratory analysis
→ renewable vs. conventional generation trends
→ solar/weather correlation
→ photovoltaic expansion analysis
→ short-term solar generation forecast
→ model limitations
```

## Highlights

- Cleaned and merged multi-year German electricity-generation data
- Investigated missing values instead of blindly dropping rows
- Compared renewable and conventional electricity generation over time
- Analyzed the nuclear phase-out in the generation data
- Compared onshore/offshore wind behavior
- Connected solar generation to weather variables such as sunshine duration and shortwave radiation
- Explored photovoltaic installation growth across German federal states
- Built a simple forecasting model for short-term solar generation
- Documented limitations and realistic improvement paths

## Why this is useful

Energy data is messy, seasonal, political, and real. The point of this project is not to pretend that one notebook solves forecasting. The point is to show the full analytics loop: ask useful questions, clean the data, visualize the signal, build a baseline model, and be honest about where the model breaks.

## Tech stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Plotly
- Folium / GeoJSON visualizations
- scikit-learn

## Repository scope

Included:

```text
README.md
LICENSE
notebooks/renewable_energy_analytics.ipynb
```

Not included:

```text
lecture slides
exercise folders
cache files
side notebooks
private environment files
full course archive
```

## Status

Portfolio-ready case study. The notebook is preserved as the main deliverable because the analysis narrative and visual interpretation are part of the work.

## License

MIT License.
