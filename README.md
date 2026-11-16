# Treasury Correlation Analysis
Preliminary statistical diagnostics financial time-series analysis

## Motivation
This project examines how implied volatility, realised yield volatility and changes in Treasury yields interact across different market conditions. The aim is to develop practical experience in financial time-series analysis, statistical modelling and quantitative research.

The project is ongoing. Subject to the availability of sufficient historical data, this framework could incorporate trading volume and desk-level revenue data. This would allow an investigation into how changes in market volatility, interest rates and broader market conditions relate to trading activity and revenue generation across different asset classes.

The longer-term objective is to move beyond analysing market indicators in isolation and towards understanding how market conditions translate into measurable commercial activity.

## Data
- 2-year and 10-year US Treasury yields.
- The 2-year / 10-year yield spread.
- The ICE BofA MOVE Index as a measure of implied Treasury volatility.
- Realised volatility calculated from daily changes in Treasury yields.
- Monthly changes in Treasury yields and the yield spread.

## Involvement
- **Data collection and cleaning:** Importing, structuring and validating historical market data.
- **Time-series analysis:** Converting daily observations into monthly features.
- **Realised volatility:** Calculating the standard deviation of daily yield changes.
- **Correlation analysis:** Examining relationships between implied and realised volatility indicators.
- **Multicollinearity diagnostics:** Using Variance Inflation Factors (VIF) to assess overlap between explanatory variables.

## Data Sources
- [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/) – 2-year and 10-year US Treasury yields.
- [Investing.com](https://www.investing.com/) – Historical ICE BofA MOVE Index data.

## Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels

