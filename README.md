# Inflation Impact Analysis with Python

**Data set 1:** https://statso.io/wp-content/uploads/2024/08/Inflation_Rates_Transformed-1.csv
**Data set 2:** https://statso.io/wp-content/uploads/2024/08/USD_INR_Exchange_Rates_1980_2024.csv

The datasets comprises historical data on the exchange rate between the Indian Rupee (INR) and the US Dollar (USD) from 1980 to 2024, along with corresponding inflation rates for India and the United States. The exchange rate data includes the average annual INR/USD exchange rate, while the inflation data captures the annual percentage change in the Consumer Price Index (CPI) for both countries. The dataset is structured with columns for the year, exchange rate, and inflation rates for each country, which enables a longitudinal analysis of the relationship between inflation and exchange rates over time.

## Inflation Impact Analysis: OVERVIEW
Inflation occurs when there is a sustained increase in the general price level of goods and services in an economy over time. It impacts various aspects of the economy, including purchasing power, consumer behaviour, savings, and investment. Moderate inflation is typically a sign of a healthy, growing economy, as it encourages spending and investment. However, high or unpredictable inflation can erode the value of money, disrupt financial planning, and lead to economic uncertainty.

To analyze the impact of inflation, we need to compare it with other economic indicators. So, to analyze the impact of inflation on the economy, we will compare it with the exchange rates over time. This comparison is important because exchange rates are influenced by inflation differentials between countries, such that higher inflation in a country generally leads to a weaker currency relative to countries with lower inflation.


## FINDINGS FROM CORRELATION ANALYSIS:
**Exchange Rate vs. Inflation Rate (India):** The correlation coefficient is approximately -0.34, which indicates a weak negative relationship. It suggests that as inflation in India increases, the INR tends to depreciate against the USD, though the relationship is not very strong.
**Exchange Rate vs. Inflation Rate (United States):** The correlation coefficient is approximately 0.24, which indicates a weak positive relationship. It suggests that higher inflation in the United States might be associated with a depreciation of the USD against the INR, but again, the relationship is not strong.
**Inflation Rate (India) vs. Inflation Rate (United States):** The correlation between the inflation rates of India and the United States is very weak and negative (-0.12), which indicates that the inflation rates in these two countries do not move together.

## FINDINGS FROM COMPARATIVE ANALYSIS:
**Early 2000s:** A period of high inflation in India coincides with a period of relative stability in the exchange rate. It suggests that factors other than inflation may have been driving the exchange rate during this time.
**Late 2000s to Early 2010s:** The period shows some alignment between rising inflation in India and a weakening INR, which indicates that inflation could be contributing to exchange rate movements.
**2015 Onwards:** The exchange rate continues to rise, while both India’s and the United States’ inflation rates remain relatively low. This divergence suggests that the exchange rate is influenced by additional factors beyond inflation, such as economic growth, monetary policy, and international trade dynamics.

## CONCLUSION:
In my analysis the inflation in India and the United States influences the exchange rate between INR and USD. Higher inflation in India generally leads to a depreciation of the INR relative to the USD, while lower inflation in the United States contributes to a stronger USD. While inflation affects the exchange rate between INR and USD, it is only one of many factors.
