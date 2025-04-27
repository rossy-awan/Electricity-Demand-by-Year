# Electricity and Renewable Growth in Indonesia and Neighbors

This project analyzes energy data for **Indonesia**, **Malaysia**, and **Singapore**, based on datasets provided by [Our World in Data](https://ourworldindata.org/energy).

## Data Source

- **Dataset:** [OWID Energy Data](https://github.com/owid/energy-data/tree/master)
- **Direct CSV Link:** [owid-energy-data.csv](https://raw.githubusercontent.com/owid/energy-data/master/owid-energy-data.csv)

The dataset includes global energy production, consumption, carbon intensity, electricity demand, and many other energy-related metrics.

## Project Structure

- **1. Data Preparation**
  - Filter for Indonesia, Malaysia, and Singapore.
  - Handle missing values (using forward fill method).
  - Select relevant energy columns for analysis (e.g., `carbon_intensity_elec`, `electricity_demand`, etc.).

- **2. Exploratory Data Analysis (EDA)**
  - Trends in electricity demand.
  - Changes in carbon intensity over time.

- **3. Forecasting**
  - Forecast future electricity demand and renewables electricity using time-series models.

## License

Data source is publicly available from [Our World in Data](https://ourworldindata.org/energy) under [Creative Commons BY license](https://creativecommons.org/licenses/by/4.0/).
