# Easy Technical Indicator

This is a custom technical indicator developed by the Forex Robot Easy Team. It is designed to detect market trends and assess their strength. The indicator is displayed on the chart window and uses a blue color for its visualization.

## Indicator Parameters

- `indicator_chart_window`: This parameter indicates that the indicator should be displayed on the chart window.
- `indicator_buffers`: This parameter specifies the number of indicator buffers used by the indicator. In this case, there is one buffer.
- `indicator_color1`: This parameter sets the color of the indicator. In this case, it is set to blue.

## Indicator Buffers

- `TrendBuffer[]`: This buffer is used to store the trend strength values calculated by the indicator.

## Custom Indicator Initialization Function

The `OnInit()` function is called during the initialization of the indicator. In this function, the indicator buffer is mapped to the corresponding index buffer using the `SetIndexBuffer()` function. The indicator name is set using the `IndicatorShortName()` function. Additional initialization code can be added to this function if needed.

## Custom Indicator Iteration Function

The `OnCalculate()` function is called for each new tick or bar to calculate the indicator values. In this function, the market trends are detected and their strength is assessed. The `calculateTrendStrength()` function is used to calculate the trend strength based on the provided price data. The calculated trend strength values are then stored in the `TrendBuffer[]` buffer.

## Custom Function to Calculate Trend Strength

The `calculateTrendStrength()` function is a custom function used to calculate the trend strength based on the provided price data. The actual calculation logic is not provided in the code and needs to be implemented by the user.

## Product Description

The Easy Technical Indicator is a powerful tool for Forex trading developed by the Forex Robot Easy Team. It is designed to detect market trends and assess their strength, helping traders make informed trading decisions.

Key Features:
- Easy to use and understand
- Customizable indicator parameters
- Accurate trend detection
- Ability to determine trend strength
- Compatible with the MetaTrader platform

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Easy Technical Indicator Review](https://forexroboteasy.com/forex-robot-review/review-easy-technical-indicator-a-powerful-tool-for-forex-trading/). To find the official developer of this product, please refer to the MQL5 platform.
