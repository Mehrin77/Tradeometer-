# Trad-O-meter by Mehrin - Financial Trading Data Analysis


This Shiny app provides a comprehensive tool for analyzing financial trading data, including stock symbols, buy/sell pressures, and market trends. Users can upload their own CSV files or use real-time data from the Dhaka Stock Exchange. The app offers dynamic gauge plots that visualize buy/sell pressure across different time intervals.

## Features

- **Upload CSV Files**: Analyze trading data by uploading CSV files.
- **Buy/Sell Pressure Visualization**: Gauge plots display the balance between buy and sell pressures as percentages.
- **Custom Time Range**: Select a custom time range to focus on specific intervals of trading data.
- **Data Cleaning**: Automatically removes irrelevant symbols and characters from trading data.
- **Dynamic Time Intervals**: Visualizes buy/sell pressures for multiple predefined time intervals.
- **Custom Plot**: Users can analyze a specified custom time range using the custom plot feature.
- **Responsive Design**: The app layout adapts to different screen sizes, ensuring all visualizations are clear and accessible.

## How to Use

1. **Upload Data**: 
   - Upload CSV files (up to 50 MB) for analysis. 
   - The data should include relevant columns such as time, stock symbols, price, change, turnover, and buy/sell information.

2. **Select Symbol**: 
   - Choose a stock symbol from the dropdown to analyze.

3. **Visualize Data**: 
   - The app generates a gauge plot for each time interval, displaying the buy/sell pressure as percentages.

4. **Custom Time Range**: 
   - Specify a start and end time in the format "HH:MM:SS" for a custom plot.
   - Click the "Analyze Custom Time" button to view the data for the selected time range.

5. **Refresh Plots**: 
   - Update visualizations with new data or select a different stock symbol for comparison.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Install the required R packages:

   ```R
   install.packages(c("shiny", "plotly", "dplyr", "ggplot2", "readr"))
   ```

3. Run the Shiny app:

   ```R
   shiny::runApp()
   ```

The project is done for LankaBangla Securities Ltd (LBSL). LBSL is the owner of the data.  

Mehrinspeedometer000.Rmd is the program and 10.06.2024 All Trade_data_OMS.csv is the dataset that can be used to run the data. 
