# Welcome to the WildinStockTips Repository! 
### Follow the investment journey and learn stock tickers to watch  -> https://tiktok.com/@wildinstocktips

## This repository is a collection of tools that I have used and customly created to assist with my investment journey
### These tools are not meant to be 100% followed and may show some inaccuracy in certain circumstances. Therefore, use these tools to assist with entries and stock purchases, but do not follow them directly. In addition RISK MANAGE!! 

## The first section within this repository is the "indicators" folder within this repository. This section is meant to be 100% compatible with tradingview. To run you can clone the repository or copy and paste directly into pine editor. 

### In order to copy and paste: 
  Step 1: visit the .pine script you would like to copy 
  Step 2: copy the script 
  Step 3: visit tradingview and log in or create a free account if needed
  Step 4: view a stock like TSM in supercharts (or the candle stick chart view)
  Step 5: Click the "pine editor" tab in the bottom left and paste the code
  Step 6: Click "add to chart" above the pine editor and this will add the indicator to chart after saving it

## OrderFlow_Core
Order Flow Trend (OFT) measures buying and selling pressure by analyzing how price moves relative to volume. It looks at whether candles close higher or lower to classify volume as buying or selling, then compares that “net volume pressure” against the candle’s price movement and range. When price rises on strong volume, OFT outputs a positive value (bullish pressure), and when price falls on strong volume, it outputs a negative value (bearish pressure). A short smoothing period makes OFT react quickly to shifts in pressure, while a long moving-average baseline helps determine trend direction. The result is a fast-responding indicator that highlights where aggressive buyers or sellers are dominating the market.

## smart_FVG
The Smart FVG Detector finds price imbalances (Fair Value Gaps) created by aggressive 3-bar moves. Its core functionality is to draw an unmitigated gap and extend it into the future until the price revisits and fills the inefficiency. It also uses a lookback limit to ensure that old or inactive gaps are automatically removed, keeping your chart clean and focused only on the most current and relevant imbalance zones that price may react to.

## zero-lag_ma
The "Automated Market Structure" script acts like a detective on your price chart, automatically highlighting the significant turning points in the market's trend. It first uses your input length (i_pivot_len) to find confirmed Swing Highs (H) and Swing Lows (L). When the price breaks one of these key structural points, the script automatically labels it: a BOS (Break of Structure), marked with a dashed line, indicates that the current trend is continuing strongly (like a ship sailing straight ahead); while a CHoCH (Change of Character), marked with a dotted line, signals the first warning that the market's trend might be reversing (like the ship turning around). This helps you quickly see whether the market is staying on track or preparing for a shift.
