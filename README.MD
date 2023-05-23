# **Apple Algorithmic Trading**

![alt text](https://github.com/Cristhian-Ninanya/Apple_Algorithmic_Trading/blob/main/images/apple_stock.png?raw=true)

**Data Set Information:**

Use real-time data for Apple's Stock Data (APPL) from the Yahoo Finance API or retrieve the dataset stored in the "Data" folder.

**Target:**
Implement an Algorithm Trading strategy known as the momentum strategy on stock price data using Python. In the momentum strategy, we buy the stocks when the momentum is positive and sell the stocks when the momentum is negative.

**Attribute Information:**

* Ticker:type of stock symbol that describes information about the stock of a company.
* Date: stock market date.
* Open:the price when the market opened in the morning.
* High:the highest price during that trading day.
* Low:the lowest price during that trading day.
* Close:the price when the market closed in the afternoon.
* Adj Close (Adjusted Close) :a price adjusted to make prices comparable over time
* Volume:number of shares of the stock traded that day.


## Real Time Dataset (1 year)

```
                         Date        Open        High         Low       Close   
35  2022-07-14 00:00:00-04:00  143.224773  148.065861  142.399698  147.588715  \
249 2023-05-19 00:00:00-04:00  176.389999  176.389999  174.940002  175.160004   
171 2023-01-27 00:00:00-05:00  142.744310  146.802484  142.664541  145.506256   
87  2022-09-27 00:00:00-04:00  152.044288  154.015265  149.266988  151.068741   
127 2022-11-22 00:00:00-05:00  147.699877  149.983220  146.503349  149.743912   

       Volume  Dividends  Stock Splits  
35   78140700        0.0           0.0  
249  55772400        0.0           0.0  
171  70555800        0.0           0.0  
87   84442700        0.0           0.0  
127  51804100        0.0           0.0  
```

## CLose Price and Momentum Strategy:

![alt text](https://github.com/Cristhian-Ninanya/Apple_Algorithmic_Trading/blob/main/images/fig1.png?raw=true)

*we can observe that when the Momentum Strategy (represented by the red line) is positive, the Close Price tends to increase. Conversely, when the Momentum is negative, the Close Price tends to decrease*

## Trading (buying/selling markers)

![alt text](https://github.com/Cristhian-Ninanya/Apple_Algorithmic_Trading/blob/main/images/fig2.png?raw=true)

*In the graph above, the buy signals are indicated by green triangle-up markers, while the sell signals are indicated by red triangle-down markers.*


**Observations:**

*  In the momentum strategy, the general approach is to buy stocks when the momentum is positive and sell stocks when the momentum is negative.

* Positive momentum suggests that the price is exhibiting upward movement or gaining strength, indicating a potential buying opportunity.

* Negative momentum indicates downward movement or weakening price, which may be considered a signal to sell or exit a position.

* By aligning buying and selling decisions with the momentum of the stocks, traders aim to capitalize on trends and take advantage of price momentum in their trading strategy.
