# Kagi Charts


## 目录
-   [DEFINITION](#definition)
-   [LINE TYPES](#line-types)
-   [LINE CALCULATION METHODS](#line-calculation-methods)
-   [USES OF KAGI CHARTS](#uses-of-kagi-charts)
-   [KAGI CHART SPECIFIC OPTIONS IN TRADINGVIEW](#kagi-chart-specific-options-in-tradingview)

# DEFINITION

Kagi Charts are a type of chart composed of vertical lines (green for up and red for down) and small horizontal lines connecting them. Similar to  [Renko Charts](https://www.tradingview.com/wiki/Renko_Charts "Renko Charts"), Kagi Charts do not factor in time. Time intervals are completely cast aside as Kagi Charts only take price action into consideration. The word Kagi is derived from the Japanese art of woodblock printing. A "Kagi" or "Key" was an L-Shaped guide used to properly align the paper for printing. Because of this, Kagi Charts are even sometimes referred to as "Key" Charts. The premise of Kagi Charts is fairly simple. Essentially, from the starting point (usually the first closing price) lines are drawn solely based on price action. The "Up" Lines (also called the yang line) are formed during  [uptrends](https://www.tradingview.com/wiki/Market_Trend#Bullish "Market Trend"), while "Down" Lines (yin lines) are formed during  [downtrends](https://www.tradingview.com/wiki/Market_Trend#Bearish "Market Trend").

<iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_764b1&symbol=WFC&interval=D&hidetoptoolbar=1&hidesidetoolbar=1&symboledit=1&saveimage=0&toolbarbg=000000&studies=&hideideas=1&theme=White&style=5&timezone=Etc%2FUTC&hidevolume=1&padding=0&studies_overrides=%7B%7D&overrides=%7B%7D&enabled_features=%5B%5D&disabled_features=%5B%5D&locale=en&utm_source=www.tradingview.com&utm_medium=widget&utm_campaign=chart&utm_term=WFC" frameborder="0" width="750" height="500"></iframe>
  
As long as prices continue to move in the current direction, the current up line or current down line will continue. Once price reverses enough (the necessary reversal amount is set by the trader), a horizontal line is drawn and then a line is drawn in the opposite direction of the previous line, stopping at the new closing price.

# LINE TYPES

**There are five different types of lines that can be drawn within a Kagi Chart.**

1.  **Up Lines (Yang Lines)**  - Form during an  [uptrend](https://www.tradingview.com/wiki/Market_Trend#Bullish "Market Trend").
2.  **Down Lines (Yin Lines)**  - Form during a  [downtrend](https://www.tradingview.com/wiki/Market_Trend#Bearish "Market Trend").
3.  **Projected Up Lines**  - During an intraday timeframe, a potential up line that would form based on current price (before actual closing price is set).
4.  **Projected Down Lines**  - During an intraday timeframe, a potential down line that would form based on current price (before actual closing price is set).
5.  **Horizontal Lines**  - Lines drawn when a line changes direction. When an up line changes to a down line, the horizontal line is considered a shoulder. When a down line changes to an up line, the horizontal line is called a waist.

# LINE CALCULATION METHODS

    
TradingView Kagi Charts use absolute values to determine line reversals. A price movement in the direction opposite of the current line, 
that exceeds the user defined reversal value, will cause a horizontal shoulder or waist to form along with a new line. 
The upside to using absolute values is that it is very straightforward and it is easy to anticipate when and where new lines will form. 
The downside is that selecting the correct reversal value for a specific instrument will take some experimentation.

  

# USES OF KAGI CHARTS

Kagi Charts are a popular charting choice because of their ease of interpretation. Because they do not take time intervals into consideration at all, they have a way of factoring out the associated  [noise](https://www.tradingview.com/wiki/Noise "Noise"). When price movement is the only  [variable](https://www.tradingview.com/wiki/Variable "Variable")  that matters, the creation of new lines gains importance. Price movements typically need to be substantial to register a line change and therefore should always be noted. Natural, small price variations that occur naturally over time can therefore be disregarded. Some common, everyday applications for Kagi Charts are the basic line reversals  [trading signal](https://www.tradingview.com/wiki/Trading_Signal "Trading Signal"),  [support and resistance](https://www.tradingview.com/wiki/Support_and_Resistance "Support and Resistance")  discovery and a sequence based reversal pattern.

**Up Line/Down Line Reversals - Steve Nison, who brought popularity to Kagi Charts, offered the most basic interpretation of the charts. It is simple, Buy on yang, sell on yin. Basically, that is buy on a reverse to an up line and sell on a reverse to a down line.**

**Support and Resistance - Kagi Charts oftentimes, reveal areas of support and resistance.**

<iframe src="https://www.tradingview.com/embed/LNEcvL93/" frameborder="0" width="750" height="500"></iframe>
  
**Nison himself proposed a trading signal which entails waiting for a sequence of nine (mostly) consecutive shoulders or waists. Traders should then look for a reversal opportunity after the ninth shoulder or waist is drawn.**

<iframe src="https://www.tradingview.com/embed/4tSfjQAz/" frameborder="0" width="750" height="500"></iframe>

# KAGI CHART SPECIFIC OPTIONS IN TRADINGVIEW

[![KagiNew.jpg](https://wiki-pics.tradingview.com/tv/public/e/e5/KagiNew.jpg)](https://www.tradingview.com/wiki/File:KagiNew.jpg)

**Up Bars**  – Change the Color and Outline of Up Bars

**Down Bars**  - Change the Color and Outline of Down Bars

**Projected Up Bars**  - Change the Color and Outline of Projected Up Bars

**Projected Down Bars**  - Change the Color and Outline of Projected Down Bars

**Reversal Amount**  – This value sets the size of a move needed to draw a new line in a different direction.