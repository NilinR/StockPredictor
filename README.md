# StockPredictor
Java Stock Prediction

The prices are stored in a List<Double> called historicalPrices

The user enters the period for the moving average. 

This determines the number of days over which the average is computed.

Method computeSMA that takes the list of prices and the period as inputs.

Then computes the SMA by summing up prices for each period and dividing by the period length.

The computed SMA values are stored in a list called movingAverages

The predicted price for the next day is the last computed SMA value.
