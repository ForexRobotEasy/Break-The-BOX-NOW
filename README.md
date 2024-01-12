# Break The BOX NOW trading robot

This code is a sample implementation of the Break The BOX NOW trading robot. It is developed by the Forex Robot Easy Team and more information can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

## Global Variables

- `EntryPips` (default value: 2): This variable represents the number of pips used as the entry point for trading.
- `ReverseMode` (default value: true): This boolean variable determines whether the robot operates in reverse mode or not.

## Trade Functions

- `PlaceBuyOrder(double price)`: This function is responsible for placing a BUY order based on the given price.

## Main Function

- `OnTick()`: This function is the main entry point for the trading logic. It checks if the reverse mode is activated and then calculates the upper and lower boundaries of the trading box based on the highest and lowest prices within the specified time period. If the current price exceeds the upper boundary of the box, a BUY order is placed using the `PlaceBuyOrder()` function.

## Additional Trade Functions

Additional trade functions can be implemented here to extend the functionality of the trading robot.

## Comments and Description

This code is a sample implementation of the Break The BOX NOW trading robot. It is designed to trade based on the breakout of a trading box defined by the highest and lowest prices within a specified time period. 

The robot operates in reverse mode, which means it looks for opportunities to enter a trade when the current price exceeds the upper boundary of the box. The `EntryPips` variable determines the size of the trading box in terms of pips.

It is important to note that this code is provided as a sample and is not the official implementation of the Break The BOX NOW trading robot. To find the official developer of this product and access detailed reviews and trading results, please visit [this link](https://forexroboteasy.com/forex-robot-review/break-the-box-now-unbiased-review-of-forex-software-ea_breakthebox/).

ForexRobotEasy is not the official developer of this product. We only provide this sample code to demonstrate how the trading robot can work based on the provided description. To find the official developer and obtain the complete and official version of this product, please visit MQL5.
