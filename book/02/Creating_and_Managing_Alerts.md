
# Creating and Managing Alerts

## 目录

-   [1、DESCRIPTION](#DESCRIPTION)
    -   [1.1、Creating alerts](#Creating_alerts)
    -   [1.2、Alerts Functions](#Alerts_Functions)
    -   [1.3、Alerts Actions](#Alerts_Actions)
    -   [1.4、Alerts for drawings](#Alerts_for_drawings)
-   [2、ALERTS TYPES](#ALERTS_TYPES)
    -   [2.1、Crossing](#Crossing)
    -   [2.2、Crossing Down / Crossing Up](#Crossing_Down_.2F_Crossing_Up)
    -   [2.3、Greater Than / Less Than](#Greater_Than_.2F_Less_Than)
    -   [2.4、Entering Channel / Exiting Channel](#Entering_Channel_.2F_Exiting_Channel)
    -   [2.5、Inside Channel / Outside Channel](#Inside_Channel_.2F_Outside_Channel)
    -   [2.6、Moving Up / Moving Down](#Moving_Up_.2F_Moving_Down)
    -   [2.7、Moving Up % / Moving Down %](#Moving_Up_.25_.2F_Moving_Down_.25)
    -   [2.8、Custom Alert Conditions](#Custom_Alert_Conditions)
-   [3、MANAGE ALERTS](#MANAGE_ALERTS)

# DESCRIPTION

TradingView alerts are immediate notifications when the market meets your custom criteria. For example, "Alert me if Apple crosses $150 up".  **All users can get visual popups, audio signals, email alerts and email-to-sms alerts. A Premium plan holder can additionally get real-time server side text message (SMS) alerts, delivered directly to his / her phone..**

Here’s a wonderful sneak peek from Chris Moody about the new alerts (view full screen for full HD resolution).

1.  [![](https://i.vimeocdn.com/video/482547543.webp?mw=500&mh=281)](https://player.vimeo.com/video/100912092?title=0&byline=0&portrait=0)

2.  [![](https://i.vimeocdn.com/video/484704436.webp?mw=500&mh=281)](https://player.vimeo.com/video/102651301?title=0&byline=0&portrait=0)

The Alerts menu can be seen on the right panel. Open it, go to the chart and create first alert:

[![Alerts panel close.png](https://wiki-pics.tradingview.com/tv/public/4/4c/Alerts_panel_close.png)](https://www.tradingview.com/wiki/File:Alerts_panel_close.png)

## Creating alerts

There are several ways to set an alert:

1. The button  **on top toolbar**:  
[![Top toolbar alert.png](https://wiki-pics.tradingview.com/tv/public/3/39/Top_toolbar_alert.png)](https://www.tradingview.com/wiki/File:Top_toolbar_alert.png)

  
2. The button  **in alerts manager window**:  
[![Manager window alert.png](https://wiki-pics.tradingview.com/tv/public/d/d1/Manager_window_alert.png)](https://www.tradingview.com/wiki/File:Manager_window_alert.png)

  
3. From the  **right-click menu**:  
[![Right click alert.png](https://wiki-pics.tradingview.com/tv/public/b/b4/Right_click_alert.png)](https://www.tradingview.com/wiki/File:Right_click_alert.png)

  
4. The button  **on drawing panel**:  
[![Drawing panel alert.png](https://wiki-pics.tradingview.com/tv/public/d/d1/Drawing_panel_alert.png)](https://www.tradingview.com/wiki/File:Drawing_panel_alert.png)

  
5.  **The tab in properties window**  of a drawing object:  
[![Properties window alert.png](https://wiki-pics.tradingview.com/tv/public/d/d1/Properties_window_alert.png)](https://www.tradingview.com/wiki/File:Properties_window_alert.png)

  
6.  **The "plus" button**  next to current price on price scale:  
[![Plus button alert.png](https://wiki-pics.tradingview.com/tv/public/9/9f/Plus_button_alert.png)](https://www.tradingview.com/wiki/File:Plus_button_alert.png)

  
7. The button  **in the chart title**:  
[![Idea alert.png](https://wiki-pics.tradingview.com/tv/public/9/94/Idea_alert.png)](https://www.tradingview.com/wiki/File:Idea_alert.png)

Alerts can be created for  **data series**,  **indicator plots**  and  **drawing objects**. Alerts on data series no depend on the time intervals, alerts for studies depend on the interval because it’s taken into account when calculating indicators.

**NOTE!**  If the indicator parameter is changed  **after the alert is created**, then alert will be triggered using  **the old settings**.

That video by Chris Moody teaches how to create a custom script based on non series studies for the alerts.  
[![](https://i.vimeocdn.com/video/499890405.webp?mw=500&mh=281)](https://player.vimeo.com/video/114269353?title=0&byline=0&portrait=0)

## Alerts Functions

When you create an alert, the following settings are available:

-  **Trigger Condition**, which determines when the alert appears.  
-  **Frequency**  - you can set whether an alert will be triggered only once or multiple times.  
-  **Timer**  which will automatically stop the alert. Alert will be automatically turned off when the Timer expiration setting is reached.  
-  **Message**  that will be shown when the alert is triggered.

## Alerts Actions

The following options are available to you, so that you can be notified about your alerts as soon as they are generated:

-  **Show Popup**  - a pop-up message will appear once an alert is triggered. If this option is enabled, a pop-up message will appear, even if you are browsing in another tab (for this feature to work properly, please allow TradingView to show desktop notifications).  
-  **Play Sound**  - once an alert is triggered, you will hear a sound.  
-  **Send Email**  - an email will be sent to you, when an alert is triggered. We will use the email address in your TradingView profile.  
-  **Send Email-to-SMS**  - use this option to receive notifications on your phone. Email-to-sms is the easiest and absolutely free way to send text message (SMS) from the internet to phones.  [This site](http://www.emailtextmessages.com/)  aims to be the most complete and up-to-date list of email addresses that can be used to send text messages to phones.  
-  **Send SMS**  - this is a premium feature that allows you to receive SMS directly to your phone, once an alert is triggered. Please note that alerts are sent as a single SMS. Your message will be shortened if it exceeds the SMS character limit. There is a monthly limit of 500 SMS.

## Alerts for drawings

Alerts are available for the following drawings:  
[![Alert for drawings.png](https://wiki-pics.tradingview.com/tv/public/7/71/Alert_for_drawings.png)](https://www.tradingview.com/wiki/File:Alert_for_drawings.png)  
  
Configure the alerts here:  
-Drawing settings panel:  
[![Alert on drawings panel.png](https://wiki-pics.tradingview.com/tv/public/e/eb/Alert_on_drawings_panel.png)](https://www.tradingview.com/wiki/File:Alert_on_drawings_panel.png)  
-Drawing properties:  
[![Alert in the drawing propertie.png](https://wiki-pics.tradingview.com/tv/public/4/47/Alert_in_the_drawing_propertie.png)](https://www.tradingview.com/wiki/File:Alert_in_the_drawing_propertie.png)  
-Right-clicking the drawing:  
[![Alert in the right-click menu.png](https://wiki-pics.tradingview.com/tv/public/8/84/Alert_in_the_right-click_menu.png)](https://www.tradingview.com/wiki/File:Alert_in_the_right-click_menu.png)  
  
If a drawing has an active alert, you’ll see an icon next to the drawing (same color as the drawing).  
[![Active alert.png](https://wiki-pics.tradingview.com/tv/public/f/f4/Active_alert.png)](https://www.tradingview.com/wiki/File:Active_alert.png)

If the alert is inactive, the icon becomes gray.  
[![Inactive alert.png](https://wiki-pics.tradingview.com/tv/public/c/c5/Inactive_alert.png)](https://www.tradingview.com/wiki/File:Inactive_alert.png)  
  
If the drawing is changed, the alert is automatically adjusted.

**Note: Drawing alerts depend on the chart resolution, just like the indicator alerts.**

# ALERTS TYPES

## Crossing

The most basic and widely used alert. Basically means, “let me know when price crosses X”. “Crossing” alert is triggered when the current price series crosses the value set when the alert was created (doesn’t matter which direction).

**Usage example:**  "I want to know when Google goes up by $10 from the current price". There are a couple of things you can do. Open a chart of GOOGL, and open the Alert menu, and the current price will be filled in the price box (right now it's 97.40). Choose Crossing and change it manually to 107.40. That's it!

Alternatively, you can right-click the chart where it says $107.40 and choose Set Alert. The 107.40 price will be filled in automatically.

## Crossing Down / Crossing Up

A more specific version of the Crossing alert. You get to specify whether a price is crossed in an upward move, or a downward move. This is useful when

"Crossing Down" alert is triggered when the current series crosses downwards the value set in the alert, and "Crossing Up" is for alerting when price crosses the value upwards.

**Usage example:**  "Microsoft is currently at 44.54. I think it will go down, and then back up to $42, at which point I'll buy because it's an upward trend. So, I want to know when MSFT crosses $42 UPWARD." So, open a chart of MSFT, and choose Crossing Up alert type and type in 42.

## Greater Than / Less Than

This alert is for when you want to know that price didn’t just bump into a level you set, but actually surpassed it.

"Greater Than" alert is triggered if the price series reaches a value that is higher than the one set in the alert. Respectively, "Less Than" alert is triggered if the series reached a value lower than the one set in the alert.

**Usage example:**  "Apple now is at $97.79 and approaching the psychlogically difficult price of $100. It's likely AAPL price will bounce off $100 a few times, but once it's through, I think it'll continue to rise steadily. Therefore, I'd like to know once the $100 barrier is bypassed for good." So, you open the AAPL chart and set the alert to Greater Than $100 for AAPL, and once the price is GREATER THAN $100, you’ll be alerted.

## Entering Channel / Exiting Channel

Channels are defined boundaries above and below a certain price. Usually channels define the "typical" random volatility of price for a stock, and a move across channel borders can be seen as a significant or an out-of-the-ordinary move by the price.

"Entering Channel" alert is triggered when the series enters the channel that was defined when the alert was created. "Exiting Channel", logically, is triggered when the series exits the channel.

Channel boundaries can be defined by the series or levels (or their combination). These alerts us the position of the previous bar relative to the channel.

**Usage example:**  "By looking at the historical price chart, Cisco's price roughly fluctuates about $2 after each earnings and then jumps. It's at $25.86 right now. Next earning are coming up soon, and I'd like to see if price moves out of the +$2 or -$2 channel from what it is now".

So, set the Exiting Channel alert with the +2 and -2 relative to the current price, and you'll be alerted.

## Inside Channel / Outside Channel

"Inside Channel" alert is triggered if the series value is within the channel and "Outside Channel" alert when the series value is out of the channel. The value should be set when creating the alert.

These alerts, unlike Entering Channel/Exiting Channel alerts, don't take into account the position of the previous bar relative to the channel.

**Usage example:**  This one is very similar to the Entering / Exiting Channel, but rather lets you know if the value is inside or outside the defined channel.

## Moving Up / Moving Down

This is the Crossing Up / Crossing Down alert with one additional parameter - time. You can get alerted if the stock goes up by $X within a certain amount of time (i.e. bars).

"Moving Up" alert is triggered if the price goes up by a certain value that you set in the alert (within a pre-specified number of bars). "Moving Down" alert does the same thing, but when the price goes down.

**Usage example:**  "I want to know if Google goes up by $10 within the next 4 days, I don’t care after that." So, you open a chart of GOOGL, and set each bar to equal 1 day. Open the Alert menu, and the current price will be filled in the price box (right now it’s 97.40). Choose Moving Up and change it manually to 107.40, and set the number of bars to 4 (since you wanted 4 days and each bar is set to 1 day). All done!

## Moving Up % / Moving Down %

"Moving Up %" alert is the same as above, but in percent. It's triggered if the price goes up by a certain percentage, which you set in the alert.  _The specified amount of bars._  Moving Down alert - when the price goes down for the set percent.

**Usage example:**  Same thing as Moving Up / Down but in percent. You don't have to calculate the target value in your head, you can simply choose UP 10% for example, and if the current price is $97.40, the target will automatically be set at $97.40 x 1.1 = $107.14

## Custom Alert Conditions

You can create custom alert conditions in Pine studies. Read more:  [https://www.tradingview.com/wiki/Alerts_in_pine](https://www.tradingview.com/wiki/Alerts_in_pine)

# MANAGE ALERTS

In  **Manage Alerts**  you can browse and edit your alerts.  
[![Manage alerts.png](https://wiki-pics.tradingview.com/tv/public/1/1e/Manage_alerts.png)](https://www.tradingview.com/wiki/File:Manage_alerts.png)

Alerts  **sorting**  functionality was added for your convenience.  
[![Alerts sorting.png](https://wiki-pics.tradingview.com/tv/public/4/4d/Alerts_sorting.png)](https://www.tradingview.com/wiki/File:Alerts_sorting.png)

Use control keys in the list to  **stop, resume, edit or delete alerts**.  
[![Control keys.png](https://wiki-pics.tradingview.com/tv/public/3/39/Control_keys.png)](https://www.tradingview.com/wiki/File:Control_keys.png)

**Double-click**  an alert to open its Edit menu.  
Move the cursor to the status tooltip and to see the reason of an alert stop:  
- an active alert has a green dot and the "Active" status.  
- a triggered alert with "Only once" setting has an orange dot and a "Triggered and Not Active" status.  
- a manually disabled or expired alert has a red dot and a "Manual Stopped" or an "Expirated" status.  
[![Status.png](https://wiki-pics.tradingview.com/tv/public/d/d0/Status.png)](https://www.tradingview.com/wiki/File:Status.png)

**Widget**  located in the chart legend will show how many alerts were created for this symbol on this resolution.  
[![Alert Widget.png](https://wiki-pics.tradingview.com/tv/public/b/bf/Alert_Widget.png)](https://www.tradingview.com/wiki/File:Alert_Widget.png)

After creating an alert a  **mark specifying its level**  (except Moving alerts) will appear on the chart. Hover your cursor over the mark to see a tooltip with a description.  
[![Alert mark.png](https://wiki-pics.tradingview.com/tv/public/d/dd/Alert_mark.png)](https://www.tradingview.com/wiki/File:Alert_mark.png)

Double-click the mark to see the Alert Edit menu. Right-click the mark to add or delete an extended alert line. You can also edit the alert value by simply dragging the label. Just move it to the desired place on the chart and the new value will be automatically applied in the Edit dialog window. When the alert is triggered, the corresponding label will be start blinking on the chart.

All triggered alerts are automatically added into  **Alerts Log**  and you can access alerts history anytime.