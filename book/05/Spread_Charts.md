# Spread Charts


## 目录

-   [1、DEFINITION](#DEFINITION)
-   [2、OPERATORS AND SETUP](#OPERATORS_AND_SETUP)
-   [3、COMMON SPREAD TYPES](#COMMON_SPREAD_TYPES)
    -   [3.1、Chart Inversions](#Chart_Inversions)
    -   [3.2、Currency Conversions](#Currency_Conversions)
    -   [3.3、Instrument Comparisons](#Instrument_Comparisons)
    -   [3.4、Exchange Arbitrage](#Exchange_Arbitrage)
    -   [3.5、Bitcoin Arbitrage](#Bitcoin_Arbitrage)
-   [4、PAIRS TRADING](#PAIRS_TRADING)

# DEFINITION

The most basic definition of a spread chart is that it is a comparison between a financial instrument (such as a stock) and an additional  [variable](https://www.tradingview.com/wiki/Variable "Variable")  (such as another financial instrument or a numerical value). Trading using spreads has been gaining in popularity because they provide a new perspective of a financial instrument's value and can also help to alleviate some risk. There are a few different ways to utilize a spread chart. Some of the more popular ones are; price inversions, currency conversions, financial instrument comparisons and pairs trading.

  

# OPERATORS AND SETUP

To create your own custom spread chart in TradingView;

1.  Enter the first variable (symbol, number etc.) in the symbol entry window in the upper left hand corner and follow it with a space.
2.  Enter one of four operators; (-) for subtraction, (+) for addition, (*) for multiplication or (/) for division and follow it with a space.
3.  Enter the second variable (symbol, number etc.) in the symbol entry window in the upper left hand corner and press the enter key.

For Example: Entering  **AAPL / XAUUSD**  will create a comparison of Apple vs. Gold by dividing Apple prices by Gold prices.

Spreads for intraday charts are calculated by taking the Open, High, Low, and Close of each 1-minute bar and then recompiled into the selected interval. This approach is the only one that results in correct spread charts. We handle all necessary calculations on our servers and display the finished spread chart in your browser.

# COMMON SPREAD TYPES

## Chart Inversions

Inverting a chart is a good way to visually chart the  [correlation](https://www.tradingview.com/wiki/Correlation "Correlation")  between two instruments. For example, with two instruments with very low correlation, inverting one of the instruments with this method will make them viewable moving in the same direction.

**For example an inversion on the EURUSD: 1/EURUSD**

<iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_60def&symbol=1%2FEURUSD&interval=D&hidetoptoolbar=1&hidesidetoolbar=1&symboledit=1&saveimage=0&toolbarbg=000000&studies=&hideideas=1&theme=White&style=1&timezone=Etc%2FUTC&hidevolume=1&padding=0&studies_overrides=%7B%7D&overrides=%7B%7D&enabled_features=%5B%5D&disabled_features=%5B%5D&locale=en&utm_source=www.tradingview.com&utm_medium=widget&utm_campaign=chart&utm_term=1%2FEURUSD" frameborder="0" width="750" height="500"></iframe>

## Currency Conversions

Multiplying or dividing an instrument by a currency pair will allow you to view the price of the instrument in a different currency.

**For Example Best Buy shown in Euros: BBY/EURUSD**
 
<iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_9d4c1&symbol=BBY%2FEURUSD&interval=D&hidetoptoolbar=1&hidesidetoolbar=1&symboledit=1&saveimage=0&toolbarbg=000000&studies=&hideideas=1&theme=White&style=1&timezone=Etc%2FUTC&hidevolume=1&padding=0&studies_overrides=%7B%7D&overrides=%7B%7D&enabled_features=%5B%5D&disabled_features=%5B%5D&locale=en&utm_source=www.tradingview.com&utm_medium=widget&utm_campaign=chart&utm_term=BBY%2FEURUSD" frameborder="0" width="750" height="500"></iframe>

## Instrument Comparisons

A common way to utilize spreads is to divide one instrument by another. This will give you spread value that can be tracked like a single instrument.

**For Example Apple vs. Gold: AAPL/XAUUSD**

<iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_b3a17&symbol=AAPL%2FXAUUSD&interval=D&hidetoptoolbar=1&hidesidetoolbar=1&symboledit=1&saveimage=0&toolbarbg=000000&studies=&hideideas=1&theme=White&style=1&timezone=Etc%2FUTC&hidevolume=1&padding=0&studies_overrides=%7B%7D&overrides=%7B%7D&enabled_features=%5B%5D&disabled_features=%5B%5D&locale=en&utm_source=www.tradingview.com&utm_medium=widget&utm_campaign=chart&utm_term=AAPL%2FXAUUSD" frameborder="0" width="750" height="500"></iframe>

## Exchange Arbitrage

Spreads can also be used to view the difference in price between the same instrument traded on two different exchanges. You will need to subtract the symbol for one exchange from the symbol from another exchange.

**For Example: BATS:FB-NASDAQ:FB**

  

## Bitcoin Arbitrage

With the rise in popularity of Bitcoins, arbitrage between BTC trading in different currencies has also become a popular trading opportunity.

**For Example: BTCUSD-BTCEUR*EURUSD**

<iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_10f62&symbol=BTCUSD-BTCEUR*EURUSD&interval=D&hidetoptoolbar=1&hidesidetoolbar=1&symboledit=1&saveimage=0&toolbarbg=000000&studies=&hideideas=1&theme=White&style=1&timezone=Etc%2FUTC&hidevolume=1&padding=0&studies_overrides=%7B%7D&overrides=%7B%7D&enabled_features=%5B%5D&disabled_features=%5B%5D&locale=en&utm_source=www.tradingview.com&utm_medium=widget&utm_campaign=chart&utm_term=BTCUSD-BTCEUR*EURUSD" frameborder="0" width="750" height="500"></iframe>

# PAIRS TRADING

Pairs trading involves trading two separate instruments simultaneously in order to execute a single trade. Pairs trading is a popular way to alleviate some of the risk of trading. The idea is that you find two highly correlated symbols (or two very lowly correlated symbols) and enter a position in both symbols. If the pair is highly  [correlated](https://www.tradingview.com/wiki/Correlation "Correlation"), they should move in the same direction. Typically, an opportunity presents itself when the pair ratio breaks through a threshold that is a certain number of standard deviations away from their average standard deviation. You would then, go long in the symbol that is under-performing and short in the symbol that is over-performing. When the pair moves back towards its average deviation, you would then close out both positions. Many technical analysts use the Bollinger Bands indicator to spot pairs trading opportunities. In example below, Bollinger Bands are set to be 2.2 Standard Deviations away from the average.

<iframe src="https://www.tradingview.com/embed/ApPXIxnV/" frameborder="0" width="750" height="500"></iframe>
  
**It is important to note a number things in regards to pairs trading.**

**1.**  A pairs trade is designed to be market neutral. This means that because of the positions that you take in two separate instruments, the direction of the market will not effect the position. The trade is designed to profit from the relationship between the two instruments, not the direction of the market itself.

**2.**Correlation moves along a scale of -1 to 1 with 1 meaning the instruments are perfectly correlated. Keep in mind that pairs trades can also work with pairs that are extremely negatively correlated (close to -1). When setting up a pairs trade with negatively correlated instruments, you would want to enter the positions when the two contracts are closer together than usual with the anticipation that they will move apart in opposite directions. In this case, you would enter positions in the same direction for both instead of going long in one and short in the other.

**3.**Another important piece of the puzzle is position size. The whole idea is to be market neutral. Therefore, you would not simply enter the same number of shares or contracts for each instrument. You would want to create the same actual dollar value in both positions. If you strictly use an equal number of shares on both sides and the dollar value of the two instruments are wildly different, then the side with the higher dollar value will have way too much weight in the trade.

**You will notice in the below example, that simply using the same number of shares for both instruments will result in an extremely unbalanced trade in terms of dollar value.**

[![Trade Size 1.PNG](https://wiki-pics.tradingview.com/tv/public/2/24/Trade_Size_1.PNG)](https://www.tradingview.com/wiki/File:Trade_Size_1.PNG)

**The number of shares should be modified in order to get the dollar values as close of possible. It will rarely (if ever) be exact but getting as close as possible is important.**

[![Trade Size 2.PNG](https://wiki-pics.tradingview.com/tv/public/0/08/Trade_Size_2.PNG)](https://www.tradingview.com/wiki/File:Trade_Size_2.PNG)

  
**4.**The key to pairs trading is the correlation between the two instruments. One thing that many traders fail to realize is that the correlation between instruments is ever changing. Even during the course of a trade, their correlation can change. This is why correlation is important to always monitor when in a pairs trade. The trader should be prepared to exit any trades which have drastic changes and correlation.

<iframe src="https://www.tradingview.com/embed/DWR7M7Tk/" frameborder="0" width="750" height="500"></iframe>