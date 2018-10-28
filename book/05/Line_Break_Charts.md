# Line Break Charts


## 目录
-   [DEFINITION](#DEFINITION)
-   [LINE TYPES](#LINE_TYPES)
-   [LINE CALCULATION METHOD](#LINE_CALCULATION_METHOD)
-   [USES OF LINE BREAK CHARTS](#USES_OF_LINE_BREAK_CHARTS)
-   [LINE BREAK CHART SPECIFIC OPTIONS IN TRADINGVIEW](#LINE_BREAK_CHART_SPECIFIC_OPTIONS_IN_TRADINGVIEW)

# DEFINITION

Line Break Charts are a Japanese chart style similar to  [Kagi](https://www.tradingview.com/wiki/Kagi_Charts "Kagi Charts")  and  [Renko Charts](https://www.tradingview.com/wiki/Renko_Charts "Renko Charts"), in that they disregard time intervals and only focus on price movements. Line Break Charts are constructed of a series of up bars and down bars (referred to as lines) . Obviously up lines represent rising prices, while down lines represent falling prices. The key to using Line Break Charts is the user defined Number of Line setting. A Line Break Chart takes the current closing price and compares it to the closing price of a previous line. The most common Number of Line setting is 3. What this means is that the closing price of the current line is compared to the closing price of the line 2  [period's](https://www.tradingview.com/wiki/Period "Period")  ago. If the current price is higher it is an up line and if it is lower, it is a down line. If the current closing price is the same or the move in the opposite direction is not large enough to warrant a reversal then no new line is drawn.

<iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_45e06&symbol=UA&interval=D&hidetoptoolbar=1&hidesidetoolbar=1&symboledit=1&saveimage=0&toolbarbg=000000&studies=&hideideas=1&theme=White&style=7&timezone=Etc%2FUTC&hidevolume=1&padding=0&studies_overrides=%7B%7D&overrides=%7B%7D&enabled_features=%5B%5D&disabled_features=%5B%5D&locale=en&utm_source=www.tradingview.com&utm_medium=widget&utm_campaign=chart&utm_term=UA" frameborder="0" width="750" height="500"></iframe>

# LINE TYPES

**There are only four types of lines**

1.  **Up Lines**  - Form during an  [uptrend](https://www.tradingview.com/wiki/Market_Trend#Bullish "Market Trend").
2.  **Down Lines**  - Form during a  [downtrend](https://www.tradingview.com/wiki/Market_Trend#Bearish "Market Trend").
3.  **Projected Up Lines**  - During an intraday timeframe, a potential up line that would form based on current price (before actual closing price is set).
4.  **Projected Down Lines**  - During an intraday timeframe, a potential down line that would form based on current price (before actual closing price is set).

# LINE CALCULATION METHOD

Each new closing price has three possible outcomes
1. New Line, Same Color - When price extends in the same direction.
2. New Line, Different Color - When the price change is large enough to warrant a reversal.
3. No New Line - When price does not change or the reversal is not large enough to warrant a new line.

The user defines the Number of Line value. The current close is then compared to a previous line close. If 3 is the user-defined value
then the current close is compared to the close 2 lines ago (the current line plus the 2 previous lines makes the total 3).
The appropriate line is then drawn (or not drawn) based on the above guidelines.

  

# USES OF LINE BREAK CHARTS

Very much like  [Kagi Charts](https://www.tradingview.com/wiki/Kagi_Charts "Kagi Charts")  and  [Renko Charts](https://www.tradingview.com/wiki/Renko_Charts "Renko Charts"), Line Break Charts are popular because of the way that they filter out  [noise](https://www.tradingview.com/wiki/Noise "Noise")  and make price movements easy to digest and understand. Some of the typical uses of Line Break Charts are; finding  [support and resistance](https://www.tradingview.com/wiki/Support_and_Resistance "Support and Resistance"), spotting  [breakouts](https://www.tradingview.com/wiki/Breakout "Breakout"), and discovering classic  [chart patterns](https://www.tradingview.com/wiki/Chart_Pattern "Chart Pattern").

**Support and Resistance - Line Break Charts oftentimes reveal areas of support and resistance.**

<iframe src="https://www.tradingview.com/embed/WeHDNSZj/" frameborder="0" width="750" height="500"></iframe>
  
**Breakouts – Breakouts occur when bars begin to generate in a defined direction after a period of trading within a support and resistance bound trading range.**

<iframe src="https://www.tradingview.com/embed/FAXbLy3L/" frameborder="0" width="750" height="500"></iframe>
  
**Classic Chart Patterns - Charts that filter out time and only focus on price, such as Line Break Charts, classical chart patterns can often be spotted.**

<iframe src="https://www.tradingview.com/embed/Egq32WJF/" frameborder="0" width="750" height="500"></iframe>

# LINE BREAK CHART SPECIFIC OPTIONS IN TRADINGVIEW

[![Neew.jpg](https://wiki-pics.tradingview.com/tv/public/4/49/Neew.jpg)](https://www.tradingview.com/wiki/File:Neew.jpg)

**Up Bars**  – Change the Color and Outline of Up Bars

**Down Bars**  - Change the Color and Outline of Down Bars

**Projected Up Bars**  - Change the Color and Outline of Projected Up Bars

**Projected Down Bars**  - Change the Color and Outline of Projected Down Bars