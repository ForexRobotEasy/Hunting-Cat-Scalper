# Hunting Cat Scalper ReadMe

This is the ReadMe file for the code of the Hunting Cat Scalper, which is a Forex trading Expert Advisor. This code is provided as a sample and can be used to understand how the Hunting Cat Scalper works. Please note that ForexRobotEasy is not the official developer of this product. To find the official developer of this product, please use MQL5.

## Input Parameters

The Hunting Cat Scalper Expert Advisor has the following input parameters:

- **Lots**: The lot size for the trades (default is 0.1).
- **StopLoss**: The stop loss level in pips (default is 100).
- **TakeProfit**: The take profit level in pips (default is 200).
- **TrailingStop**: The trailing stop level in pips (default is 50).

## Global Variables

The code uses the following global variables:

- **entryPrice**: Stores the entry price of the current trade.
- **stopLossLevel**: Stores the calculated stop loss level.
- **takeProfitLevel**: Stores the calculated take profit level.
- **trailingStopLevel**: Stores the calculated trailing stop level.
- **ticket**: Stores the ticket number of the current trade.

## Expert Initialization

The **OnInit()** function is called during the Expert Advisor initialization. In this function, the stop loss, take profit, and trailing stop levels are calculated based on the input parameters. The calculated levels are then printed for reference.

## Expert Tick Function

The **OnTick()** function is called on every tick of the price. In this function, the code checks if a pending order exists. If the order is closed, a new order is opened using the **OrderSend()** function. The stop loss, take profit, and trailing stop levels are updated based on the current price, and the updated levels are printed for reference.

## Expert Deinitialization

The **OnDeinit()** function is called when the Expert Advisor is being deinitialized. In this function, the open order is closed using the **OrderClose()** function.

## Product Description

The Hunting Cat Scalper is a professional Forex trading Expert Advisor that aims to profit from short-term price movements. It uses a combination of stop loss, take profit, and trailing stop levels to manage trades effectively and minimize losses.

With the Hunting Cat Scalper, you can customize the lot size, stop loss, take profit, and trailing stop levels according to your trading strategy and risk tolerance. The Expert Advisor opens and closes trades automatically based on the market conditions and the specified levels.

Key Features:
- Customizable lot size
- Adjustable stop loss, take profit, and trailing stop levels
- Automatic trade management
- Suitable for short-term trading

For detailed reviews and trading results of the Hunting Cat Scalper, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/hunting-cat-scalper-review-a-professional-forex-traders-perspective/). Please note that ForexRobotEasy is not the official developer of this product. We only show sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
