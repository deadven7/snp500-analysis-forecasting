# S&P 500 Regression and Time Series Analysis Project

## Project Overview
This project conducts an in-depth analysis and forecasting of the S&P 500 index, focusing specifically on how significant world events from 2019 to 2022 have impacted the index and on forecasting the future valuation of Pfizer within the index.

## Project Activities and Methodology
### Data Collection
- **Source**: The project utilized a rich dataset from Kaggle that includes detailed trading data (open, high, low, close prices and volume) of stocks from 2019 to 2022.
- **Selection Criteria**: Only data post-2019 was considered due to its relevance in capturing the impact of recent global events.

### Data Processing and Analysis
- **Normalization**: Data across different sectors was normalized to ensure uniformity in scale, facilitating accurate comparisons.
- **Sector Analysis**: The S&P 500 was segmented into 11 key sectors. Each sector was individually analyzed to determine its responsiveness and influence on the broader index.
- **Event Impact Study**: Specific events such as the COVID-19 pandemic, geopolitical conflicts, and significant political events were studied for their impact on the sectors and the overall index.

### Statistical and Predictive Analysis
- **Trend Visualization**: Employed line graphs for trend analysis, candlestick charts for volatility insights, and box plots to understand distribution and outliers within the data.
- **Comparative Sector Analysis**: Conducted to highlight the differential impacts of global events on various sectors. This analysis helps identify which sectors and companies are more resilient or more volatile in response to external shocks.
- **Forecasting Model**: An ARIMA model was specifically chosen for its effectiveness in understanding and predicting time series data. The model was tailored to forecast Pfizer's stock performance, considering its historical data patterns and market position.

### Time Series Forecasting
- **Stationarity Testing**: Utilized Augmented Dickey-Fuller tests to confirm the stationarity of the time series, a prerequisite for reliable ARIMA modeling.
- **Model Selection and Fitting**: Auto ARIMA was used to systematically explore various model parameters (p, d, q) and select the optimal model based on the lowest AIC (Akaike Information Criterion).
- **Model Evaluation**: The chosen ARIMA model was rigorously tested using diagnostic checks like the Ljung-Box test to ensure the absence of autocorrelation in residuals, confirming the model's adequacy.

## Key Findings
- **Sector-Specific Responses**: The analysis highlighted that sectors like Healthcare exhibited growth during the pandemic, whereas sectors such as Energy were adversely affected during geopolitical tensions.
- **Forecasting Insights**: The ARIMA model forecasts for Pfizer indicate its likely future trajectory and potential market behaviors, providing a predictive outlook that can be invaluable for strategic planning.

## Visual Insights
Below are key visualizations from the project, demonstrating the analytical depth and insights garnered:

### S&P 500 Cumulative Analysis

![image](https://github.com/deadven7/snp500-analysis-forecasting/assets/43636138/5c038d03-5efb-4080-9708-fd04f8584eee)

![image](https://github.com/deadven7/snp500-analysis-forecasting/assets/43636138/16e9a314-f76e-4aeb-b3e7-59cfad3114fe)


### Sector-wise Performance Trends

![image](https://github.com/deadven7/snp500-analysis-forecasting/assets/43636138/79d32cd0-0823-4a87-9ee5-fd60b734e454)

![image](https://github.com/deadven7/snp500-analysis-forecasting/assets/43636138/47c80e5f-e054-4cf9-bd63-f2c414f07abf)


### Pfizer Stock Forecast

![image](https://github.com/deadven7/snp500-analysis-forecasting/assets/43636138/975db89d-7df5-48f3-bdee-32391c2aed27)

## Conclusion
This project successfully applies complex statistical techniques and machine learning models to provide a nuanced understanding of the S&P 500's dynamics and forecasts. These insights not only enhance our understanding of the index but also aid in strategic decision-making regarding stock investments.

## Team
- Amaan Vora
- Jahnavi Shah
- Noopur Singh
- Ganesh Raj K

### Acknowledgments
We extend our gratitude to all data providers and contributors who supported the analytical endeavors of this project.
