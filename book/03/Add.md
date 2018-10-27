
# Add

<script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>

# APPLICATION

The add function allows users to overlay additional symbols or data series over top of the existing chart. This is different than the  [compare](https://www.tradingview.com/wiki/Compare "Compare")  function in that the chart does not change the vertical axis from price to percentage and auto-scale to fit both. The vertical axis stays aligned with the chart's original data series. The new symbol/data series is merely overlaid on top. This allows for the actual price value of both data series to be visible without the chart collapsing if the values are too far apart. The add function is good for visual comparisons between two or more symbols.

**The example below is an example of a chart containing the EURUSD and the EURJPY.**

<script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
<!-- TradingView Widget BEGIN -->
<div id="tv-idea-preview-1820d"></div>
<script type="text/javascript">
new TradingView.IdeaWidget({
    "container_id": "tv-idea-preview-1820d",
    "width": "100%",
    "height": 450,
    "idea": "64uhU1Dg",
    "locale": "zh_CN"
});
</script>
<!-- TradingView Widget END -->

  
A popular reason for using the add function is the ability to compare market trends for several similar or related instruments simultaneously. For example, analyzing two different gold tracking ETFs to spot minor differences.

**The example below is a chart containing two separate gold tracking ETFs. They are obviously quite closely related but careful examination shows that minor differences do occur.**

<!-- TradingView Widget BEGIN  -->
<div id="tv-idea-preview-1821d"></div>
<script type="text/javascript">
new TradingView.IdeaWidget({
  "container_id": "tv-idea-preview-1821d",
  "width": "100%",
  "height": 300,
  "idea": "oAdBwynY",
  "locale": "zh_CN"
});
</script>
<!-- TradingView Widget END -->

# HOW TO USE IN TRADINGVIEW

To add a new symbol to overlay on top of the current data series/chart, simply click on the "Add" button on the toolbar along the top of the chart and type the symbol into the dialogue box and click the + sign.

[![AddInput2.png](https://wiki-pics.tradingview.com/tv/public/c/c5/AddInput2.png)](https://www.tradingview.com/wiki/File:AddInput2.png)

  
Another option is the "Overlay the main chart" feature. If this is unchecked, the new symbol will not be overlaid on top of the original data series, it will be sent to a new panel beneath the original one. This allows for greater control of each data series even though it can hinder direct, visual comparisons.

<!-- TradingView Widget BEGIN -->
<div id="tv-idea-preview-1822d"></div>
<script type="text/javascript">
new TradingView.IdeaWidget({
  "container_id": "tv-idea-preview-1822d",
  "width": "100%",
  "height": 450,
  "idea": "YJi5Atqr",
  "locale": "zh_CN"
});
</script>
<!-- TradingView Widget END -->
