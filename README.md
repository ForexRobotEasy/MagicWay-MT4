# MagicWay MT4

MagicWay MT4 is a professional forex trader's automatic trading system developed by the Forex Robot Easy Team. This expert advisor is designed to execute trading operations for multiple currency pairs based on the MagicWay trading algorithm.

## Global Variables

- supportedPairs: An array of supported currency pairs. The current supported pairs are AUDNZD, NZDCAD, and AUDCAD.
- chartTimeframe: The chart timeframe to be used for trading operations. The default value is PERIOD_M1.

## Expert Advisor Functions

### OnInit()

This function is called during the initialization of the expert advisor. It registers the supported currency pairs by calling the SymbolSelect() function.

### OnTick()

This function is called on every tick of the chart. The trading logic goes here. You can add your trading strategy in this function.

## Helper Functions

### SetChartTimeframe(int timeframe)

This function sets the chart timeframe for trading operations. It uses the ChartSetInteger() function to set the CHART_PERIOD property of the chart.

## Execution Entry Point

### OnStart()

This function is called when the expert advisor starts. It sets the chart timeframe to the first currency pair and then calls the RunMagicWay() function.

### RunMagicWay()

This function performs trading operations for the supported currency pairs. It loops through each pair, performs trading operations specific to that pair, and prints a success message.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - MagicWay MT4 Review](https://forexroboteasy.com/forex-robot-review/review-magicway-mt4-a-professional-forex-traders-automatic-trading-system/).

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
