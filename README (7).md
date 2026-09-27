# Sales Forecast Preparation

## Project Overview

This project prepares historical sales data for a simple sales forecasting analysis.

The main focus is to convert transaction-level sales data into a consistent monthly time series and visualize the monthly sales trend using Excel and Python (Pandas).

## Objectives

- Prepare historical sales data in a monthly time-series format
- Calculate total sales for each month
- Check for missing months
- Create a simple monthly sales trend chart
- Prepare the data for possible forecasting work

## Tools Used

- Excel
- Python
- Pandas
- Matplotlib

## Dataset

The project uses a Superstore sales dataset containing order-level sales information, including order dates and sales values.

## Work Completed

### Excel

- Organized sales data by month using the Order Date
- Calculated monthly total sales using `SUMIFS`
- Created a Prepared Time Series with Month and Total Sales
- Created a Monthly Sales Trend line chart

### Python

- Loaded the dataset using Pandas
- Converted Order Date into a proper date format
- Created a Month column
- Grouped sales by month
- Calculated monthly total sales
- Checked for missing monthly values
- Created a Monthly Sales Trend chart using Matplotlib

## Project Structure

```text
Sales-Forecast-Preparation/
│
├── Sales_Forecast_Preparation.xlsx
├── Sales_Forecast_Preparation.ipynb
└── README.md
```

## Result

The final prepared time series contains monthly sales data covering the historical period in the dataset. The trend chart provides a simple view of how sales changed over time and prepares the data for further forecasting analysis.

## Note

This project focuses on data preparation and trend visualization. No forecasting model or machine learning method is included.
