# Regression Trend

## 目录

-   [1、APPLICATION](#APPLICATION)
-   [2、HOW TO USE IN TRADINGVIEW](#HOW_TO_USE_IN_TRADINGVIEW)
    -   [2.1、Inputs](#Inputs)
        -   [2.1.1、Upper Deviation](#Upper_Deviation)
        -   [2.1.2、Lower Deviation](#Lower_Deviation)
        -   [2.1.3、Use Upper Deviation](#Use_Upper_Deviation)
        -   [2.1.4、Use Lower Deviation](#Use_Lower_Deviation)
    -   [2.2、Style](#Style)
        -   [2.2.1、Base](#Base)
        -   [2.2.2、Up](#Up)
        -   [2.2.3、Down](#Down)
        -   [2.2.4、Pearson's R](#Pearson.27s_R)
        -   [2.2.5、Extend Lines](#Extend_Lines)
        -   [2.2.6、Background](#Background)
    -   [2.3、Coordinates](#Coordinates)
        -   [2.3.1、Point 1 Bar](#Point_1_Bar)
        -   [2.3.2、Point 2 Bar](#Point_2_Bar)

# APPLICATION

Regression Trends can be used in a way similar to  [parallel channels](https://www.tradingview.com/wiki/Parallel_Channel "Parallel Channel"). The main difference is that there are upper and lower bands which are set a user defined number of  [standard deviations](https://www.tradingview.com/wiki/Standard_Deviation "Standard Deviation")  away from a base line. This is a good tool to use to determine when a price is unusually far away from its baseline.

<iframe src="https://www.tradingview.com/embed/JtAvFXCO/" frameborder="0" width="750" height="500"></iframe>

# HOW TO USE IN TRADINGVIEW

1.  **Navigate to  [https://www.tradingview.com/](https://www.tradingview.com/)**
2.  **On the landing page, enter a symbol and click "Launch Chart"**
3.  **Drawing Tools are located along the left hand side of the chart. Select the Drawing Tool that you would like to add to your chart.**
4.  **You can access the Formatting Window by right clicking on the Drawing Tools in the chart itself and selecting "Format".**

## Inputs

[![RegressionTrendInputs.PNG](https://wiki-pics.tradingview.com/tv/public/d/da/RegressionTrendInputs.PNG)](https://www.tradingview.com/wiki/File:RegressionTrendInputs.PNG)

### Upper Deviation

Determines the number of standard deviations away from the base to set the upper channel. Essentially this sets the distance between the center base and the edge of the upper channel.

### Lower Deviation

Determines the number of standard deviations away from the base to set the lower channel. Essentially this sets the distance between the center base and the edge of the lower channel.

### Use Upper Deviation

Toggles the use/visibility of the upper channel.

### Use Lower Deviation

Toggles the use/visibility of the lower channel.

## Style

[![RegressionTrendStyle.PNG](https://wiki-pics.tradingview.com/tv/public/a/a9/RegressionTrendStyle.PNG)](https://www.tradingview.com/wiki/File:RegressionTrendStyle.PNG)

### Base

Can change the color of the base line as well as its thickness and line style. Can also toggle its visibility.

### Up

Can change the color of the upper channel as well as its border's thickness and line style. Can also toggle its visibility.

### Down

Can change the color of the lower channel as well as its border's thickness and line style. Can also toggle its visibility.

### Pearson's R

Can toggle the visibility of text displaying Pearson's correlation coefficient value between the two points.

### Extend Lines

Toggles the option to extend the channel lines indefinitely to the right, even when out of the current chart view.

### Background

Can change the opacity level of the background.

## Coordinates

[![RegressionTrendCoordinates.PNG](https://wiki-pics.tradingview.com/tv/public/3/3e/RegressionTrendCoordinates.PNG)](https://www.tradingview.com/wiki/File:RegressionTrendCoordinates.PNG)

### Point 1 Bar

Allows for the precise placement of the regression trend's first point using a bar number.

### Point 2 Bar

Allows for the precise placement of the regression trend's second point using a bar number.