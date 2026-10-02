# Renewable Energy Analytics

A data-analytics case study on Germany's electricity generation from 2018–2023, focused on renewable-energy growth, photovoltaic expansion, weather correlations, and short-term solar-generation forecasting.

The project started as a university data analytics assignment and has been cleaned into a compact portfolio artifact: one self-contained notebook, one clear story, no lecture dump.

## What this analyzes

- Germany's electricity mix from 2018 to 2023
- Renewable vs. non-renewable generation trends
- Wind onshore vs. offshore generation patterns
- Solar generation and seasonal/weather effects
- Photovoltaic expansion across German federal states
- A simple forecasting model for solar electricity generation

## Main artifact

Open the notebook:

```text
notebooks/renewable_energy_analytics.ipynb
```

It contains the full workflow:

```text
data preparation → data quality checks → exploratory analysis → weather correlation → photovoltaic expansion → forecasting
```

## Highlights

- Cleaned and merged multi-year German electricity-generation data
- Interpreted missing values and data quality issues instead of blindly dropping rows
- Compared renewable and conventional electricity generation over time
- Linked solar generation to weather variables such as sunshine duration and shortwave radiation
- Analyzed photovoltaic installation growth across Germany
- Built a basic regression-style forecast for short-term solar generation
- Discussed model limitations and improvement paths

## Why it matters

Energy data is messy, seasonal, political, and very real. This project is less about chasing a perfect model and more about showing the full data-analytics loop: asking useful questions, cleaning the data, visualizing patterns, and being honest about what the model can and cannot predict.

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

This repository intentionally contains only the cleaned portfolio artifact. Original lecture slides, exercises, cache files, side notebooks, and course material were left out.

## License

MIT License.
