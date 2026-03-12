# Global Holidays & Air Travel Analysis

This project explores the relationship between national holiday calendars and global air travel demand. By analyzing data across 36 countries, the study investigates how cultural and public holidays influence passenger volumes for both domestic and international flights.

## Project Overview
Air travel is highly seasonal, but the degree to which specific holiday clusters drive spikes in demand varies by region. This project utilizes the "Global Holidays and Travel" dataset to quantify these patterns and determine if holiday frequency is a reliable predictor of airport traffic.

## Key Insights & Methodology
* **Standardized Comparisons:** Used **Z-score normalization** to compare travel intensity across countries with vastly different population sizes and infrastructure.
* **Statistical Correlation:** Applied **Pearson correlation coefficients** to measure the strength of the relationship between the number of holidays in a month and passenger recovery rates.
* **Trend Analysis:** Identified that while many countries experience travel surges during holiday months, the "holiday effect" is often moderated by broader economic and seasonal factors.
* **Visual Storytelling:** Developed interactive visualizations to map travel intensity across different latitudes and timeframes.

## Technical Stack
* **Language:** Python
* **Data Libraries:** `Pandas`, `NumPy`
* **Visualization:** `Plotly` (for interactive charts), `Seaborn`, `Matplotlib`, and `Plotnine` (Grammar of Graphics for Python)
* **Environment:** Jupyter Notebook

## Repository Contents
* `flightholidays.ipynb`: The complete analysis including data cleaning, processing, and statistical modeling.
* `flightholidays.html`: A rendered version of the notebook. **Note:** This file allows for the viewing of interactive Plotly graphs directly in a web browser without requiring a Python environment.

## How to View
1. **Interactive Version:** Download the `flightholidays.html` file and open it in any modern web browser.
2. **Code & Analysis:** Open `flightholidays.ipynb` in Jupyter Lab, VS Code, or Google Colab to view the source code and methodology.