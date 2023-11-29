# UPD1 Volume TimeFrame POC

This code is a custom indicator for MetaTrader 5 that calculates the Point of Control (POC) based on the volume of a specified timeframe. The POC represents the price level at which the highest volume of trades occurred.

## Indicator Settings

- **TimeFrame**: The timeframe to calculate the POC on. The default value is 15 minutes.
- **ConnectLines**: Determines whether to connect the POC lines or keep them separate. The default value is true.

## How It Works

1. The indicator initializes by setting up the indicator buffers and labels.
2. During the calculation, the indicator scans all the bars and identifies the bar with the highest volume on the selected timeframe.
3. The POC line values are then set based on the selected ConnectLines option. If ConnectLines is true, both the upper and lower POC lines will have the same volume value. If ConnectLines is false, the lower POC line will have a volume value of 0.
4. The indicator returns the total number of calculated bars.

Please note that this code is provided as a sample and is not developed by Forex Robot Easy Team. The official developer of this product can be found on the MQL5 website.

For detailed reviews and trading results of this product, visit [Forex Robot Easy - UPD1 Volume TimeFrame POC Review](https://forexroboteasy.com/forex-robot-review/upd1-volume-timeframe-poc-review-optimize-forex-trading/).

For more information and official development of this product, please refer to MQL5.
