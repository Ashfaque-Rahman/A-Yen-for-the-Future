# A Yen for the Future

## Summary
In this analysis, we are trying to determinene future movements in the value of the Canadian dollar versus the Japanese Yen. Based on the analysis result, we will determine whether it will be feasible to invest in Japanese Yen or Not?

#### Time-Series Forecasting
    * Based on this Time Series Analysis on the historical data of CAD to JPY, we found that since 1990, Japanese Yen had been getting stronger each year against Canadian Dollar. Although it did have an fallout during 2007-2008 financial crisis but it recovered very quickly and now the Japanese Yen has a trend of becoming more stronger against Canadian Dollar. Based on some other investment factor it would be safe to assume that the idea of investing in Japanese Yen is relatively a good option considering Canada's and Japan's respective economic policies, unemployment rates, exports and imports, statics and GDP growth etc.


#### Linear Regression Forecasting
    * Based on this Linear Regression Forecasting, we have built a Scikit-Learn linear regression model to predict CAD/JPY returns with *lagged* CAD/JPY futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).
    * After training on a test data, we trained a model to predict on a dataset which it had not been seen yet. The result is quite satisfactory. The out-of-sample RMSE is lower than the in-sample RMSE. So I think this model performed better on out-of-sample data as compared to in-sample data.
    
## Conclusion
Based on the above two analysis, we can conclude that we need more data and analysis to decide whether it is safe to invest in Japanese Yen. But if we can guess roughly based on our results, it will not be a bad idea to start thinking on investing on Japanese Yen. I mean that's a good start on further analysis as well