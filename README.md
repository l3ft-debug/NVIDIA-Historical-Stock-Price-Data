# NVIDIA Price Trend Analysis

This repository contains a comprehensive Google Colab notebook for analyzing the historical stock prices of NVIDIA. The notebook helps you explore trends, volatility, seasonality, and volume-price relationships in NVIDIA's stock using visualizations and statistical techniques.

## Features

- **Data Visualization**: Plots daily, monthly, and yearly closing prices.
- **Moving Averages**: Overlays 50-day and 200-day moving averages to distinguish long-term growth from short-term fluctuations.
- **Returns & Volatility**:
  - Calculates daily percentage returns.
  - Visualizes return distributions (histograms).
  - Computes and charts rolling 30-day volatility to reveal “calm” vs. “wild” periods.
- **Volume Analysis**:
  - Scatter plot of absolute daily returns vs. trading volume.
  - Highlights if big price moves coincide with large trading volumes.
- **Intraday Range**: Analyzes and plots the daily high-low range (market uncertainty).
- **Seasonality**:
  - Groups returns by year/month.
  - Shows which months historically yield higher returns.
  - Includes a seasonal heatmap of returns.

## Usage

1. **Upload Data**: You must provide the NVIDIA historical stock data CSV file (e.g., `HistoricalData_1754061510662.csv`). The notebook will prompt you to upload this file.
2. **Run Notebook**: Open the notebook in Google Colab and run all cells. All analysis and plots will be generated automatically.
3. **Customize**: Feel free to modify rolling window sizes, groupings, or plot styles as desired.

## File Structure

- `Price_Trend_Analysis_NVIDIA.ipynb` — Main notebook for all analysis and visualizations.
- `README.md` — This file; overview and instructions.

## Requirements

- Google Colab (recommended) or local Jupyter Notebook with the following Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly

All dependencies are installed automatically in the first cell of the notebook.

## Example Outputs

- Line plots of daily/monthly/yearly closing prices
- Overlaid moving averages
- Histogram of daily returns
- Rolling volatility chart
- Scatter plot: absolute return vs. volume
- Market range (intraday high-low) over time
- Seasonal heatmap of returns

## License

This project is provided for educational and research purposes.

---

**Contributions and suggestions are welcome!**