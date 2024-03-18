# Pivot Points Daily Indicator

This is a custom indicator for MetaTrader 5 (MQL5) called 'Pivot Points Daily'. It calculates and plots the pivot points, as well as the support and resistance levels, on the chart. The indicator is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/pivot-points-daily-mt4-review-customizable-forex-indicator/).

## Indicator Settings

- Number of Days: This parameter determines how many days the indicator will consider when calculating the pivot points. By default, it is set to 5.

## Indicator Line Colors and Styles

The indicator plots the following lines on the chart:

- Pivot: LimeGreen color, solid line style.
- R1 (Resistance 1): Orange color, solid line style.
- R2 (Resistance 2): Magenta color, solid line style.
- R3 (Resistance 3): Red color, solid line style.
- S1 (Support 1): DodgerBlue color, solid line style.
- S2 (Support 2): Black color, solid line style.
- S3 (Support 3): Gray color, solid line style.

## Indicator Calculation

The indicator calculates the pivot points, support, and resistance levels based on the high, low, and close prices of the selected period. It excludes Sundays from the calculation.

For each bar in the selected period, the indicator calculates the following values:

- Pivot: (High + Low + Close) / 3
- R1: (2 * Pivot) - Low
- R2: Pivot + (High - Low)
- R3: High + 2 * (Pivot - Low)
- S1: (2 * Pivot) - High
- S2: Pivot - (High - Low)
- S3: Low - 2 * (High - Pivot)

## Product Description

This code represents a sample implementation of the 'Pivot Points Daily' indicator for MetaTrader 5. It is provided as a reference and demonstration of how the indicator works.

Please note that Forex Robot Easy is not the official developer of this product. We only provide a review and trading results on our website [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/pivot-points-daily-mt4-review-customizable-forex-indicator/). To find the official developer of this product and access the full version, please visit the MQL5 marketplace.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/pivot-points-daily-mt4-review-customizable-forex-indicator/).

## Disclaimer

This code is provided as a sample and demonstration of the 'Pivot Points Daily' indicator. The actual performance and results may vary depending on various market conditions and trading strategies. It is recommended to thoroughly test the indicator and consult with professional traders before using it in live trading.

Please refer to the official developer and documentation of this indicator for more information and support.
