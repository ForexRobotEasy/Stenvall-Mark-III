# Stenvall Mark III

Stenvall Mark III is a reliable Forex robot developed by the Forex Robot Easy Team. This code is an example of how the Stenvall Mark III robot works and can be used as a reference for understanding its functionality. Please note that ForexRobotEasy is not the official developer of this product. To find the official developer, please refer to MQL5.

## Table of Contents
- [Dependencies](#dependencies)
- [Global Variables](#global-variables)
- [Trading Parameters](#trading-parameters)
- [Main Trading Function](#main-trading-function)
- [Trend Strategy](#trend-strategy)
- [Countertrend Strategy](#countertrend-strategy)
- [Signal Accuracy Calculation](#signal-accuracy-calculation)

## Dependencies
This code requires the following libraries and dependencies:
- Trade.mqh
- Trading.mqh
- Utilities.mqh

## Global Variables
The global variables used in this code are:
- trade: an instance of the CTrade class
- trading: an instance of the CTrading class
- utilities: an instance of the CUtilities class

## Trading Parameters
The following trading parameters can be adjusted:
- nightStartHour: the start of night scalping trading hours
- nightEndHour: the end of night scalping trading hours
- signalAccuracy: the minimum accuracy of trading signals
- maxDrawdown: the maximum allowable drawdown

## Main Trading Function
The main trading function, `OnTick()`, is executed on every tick. It checks if it is within the specified night scalping trading hours and performs the corresponding trades based on the trend and countertrend strategies. It also checks the trading signals accuracy before executing a trade.

## Trend Strategy
The `CTrading::TrendStrategy()` function implements the trend strategy logic. This function should be modified to include the specific logic for the trend strategy. It should return true if a trend trade should be executed, false otherwise.

## Countertrend Strategy
The `CTrading::CountertrendStrategy()` function implements the countertrend strategy logic. This function should be modified to include the specific logic for the countertrend strategy. It should return true if a countertrend trade should be executed, false otherwise.

## Signal Accuracy Calculation
The `CUtilities::GetSignalAccuracy()` function calculates the signal accuracy based on a specific logic. This function should be modified to include the specific logic for calculating the signal accuracy. It should return the calculated signal accuracy percentage.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/stenvall-mark-iii-review-reliable-forex-ea-for-long-term-investment/).
