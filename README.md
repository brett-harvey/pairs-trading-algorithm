# Pairs Trading Cryptocurrency Bot
This is a pairs trading algorithm for the Bitfinex Cryptocurrency Exchange.

### The Goal of this Project
The goal for this project is to give you two USD pairs for cryptocurrencies. You will then have the option to open two margin positions, one long postion and one short position. 

### Determining the Price Ratio between two pairs - The 'fair' value
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

