# Buy/Sell Volume By Time Bars

This Pine Script indicator is designed to enhance your TradingView chart analysis by displaying buy and sell volume by time bars. It features two customizable metrics to gauge a baseline volume. The indicator offers a simple moving average as well as a median. The median is calculated by taking the median of the last "volumic metric length" bars from the same session (regular session, extended session). The median during the regular market session will only be calculated using regular market session data and vice versa for extended hours. This method of calculation provides a more accurate baseline volume than the simple moving average.

## Features

- **Show Volume Metric:** Toggle to display or hide the volume metric.
- **Volume Metric Display:** Choose between 'Line' or 'Bars' format for displaying the volume metric.
- **Volume Metric:** Select the type of volume metric, either 'SMA' (Simple Moving Average) or 'Median'.
- **Volume Metric Length:** Adjust the length for the volume metric calculation (range: 10 to 500).
- **Volume Median Session Data:** Choose between 'Regular' and 'Extended' session data for the volume median calculation.
- **Only Show Regular Session Volume Median Higher Than Timeframe:** Set the timeframe at which any greater timeframe only shows the regular session median, even over extended session bars. 
- **Futures Regular Session:** Define the time range for the futures regular session.
- **Buy/Sell Volume Colors:** Customize the colors for buy and sell volume.
- **Volume Metric Bars & Line Colors:** Choose colors for the volume metric bars and line.

## How to Use

1. Copy the provided Pine Script code.
2. Open TradingView and create or edit a chart.
3. Click on the "Pine Script" tab, paste the code into the editor, and save the script.
4. Apply the indicator to your chart by selecting it from the list of available indicators.
5. Configure the indicator's settings according to your preferences.
6. The chart will now show the buy/sell volume by time bars at the bottom. Below is an example of the indicator on the SPY 5m chart.

![Example Buy/Sell Volume Bars on SPY 5m chart](https://i.imgur.com/vKdKWDJ.png)
