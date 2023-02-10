# Trend Following Strategy

### Overview: 

1. Data Collection:
   - Use ByBit's API to get data from n days in the past.

2. Strategy:
   - Identify local resistance levels and long at next testing, ideally catching a breakout rally.
   - Intialize stop-loss and take-profit parameters to basic random parameters(1.25%).
   - Get plots of entries and exits.
   <p align="center">
   <img src = 'https://github.com/Jim2E/bybit_trend_following/blob/main/non_optimized_parameters/entries_exits.png' width = "680">
   </p>
   <p align="center">
   <img src = 'https://github.com/Jim2E/bybit_trend_following/blob/main/non_optimized_parameters/pnls.png' width = "580">
   </p>
   <p align="center">
   <img src = 'https://github.com/Jim2E/bybit_trend_following/blob/main/non_optimized_parameters/fund_performance.png' width = "580">
   </p>
3. Analysis:
   - Optimize risk-parameters using grid search to find better parameters.
   - Get plots of simulated perpetual trade pnls and fund performance. 
   <p align="center">
   <img src = 'https://github.com/Jim2E/bybit_trend_following/blob/main/optimized_parameters/entries_exits.png' width = "680">
   </p>
   <p align="center">
   <img src = 'https://github.com/Jim2E/bybit_trend_following/blob/main/optimized_parameters/pnls.png' width = "680">
   </p>
   <p align="center">
   <img src = 'https://github.com/Jim2E/bybit_trend_following/blob/main/optimized_parameters/fund_performance.png' width = "680">
   </p>
