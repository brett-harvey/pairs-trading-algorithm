# BitMEX Pairs Trading Cryptocurrency Bot
This is a pairs trading algorithm for the Bitfinex Cryptocurrency Exchange.
##### Official BitMEX Website: https://www.bitmex.com/

##### The Goal of this Project
The goal for this project is to utilize a pair-trading strategy to trade BitMEX Futures contracts.

BitMEX Markets - As of June 5th 2018 
* **XBTUSD**
* **ADAM18**
* **BCHM18**
* **ETHM18**
* **LTCM18**
* **XRPM18**

#### Determining the Price Ratio between two pairs - The 'fair' value
We want to determine which USD pairs have the closest 'fair' value to one another.

##### Parameters
```
>>> fair all
```
Return all fair values and rank top to bottom

```
>>> fair btc-eos
```
Return fair values for two specific USD pairs

