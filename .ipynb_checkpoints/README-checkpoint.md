# Portfolio-Optimization

1. Data Collection and Manipulation:
   - Data of 'Ajd Close' of approximately 100 tickers from 1st Jan 2018 to 1st Jan 2024.
   - Tickers and Data is filtered based on sectors.
  
2. Feature Engineering:
   - The features used in regression are Log Returns, PE Ratio, Beta.

   - Log Returns:
     - 
     
   - PE Ratio (Price-to-Earnings):
     - PE Ratio = Market Value per Share / Earnings per Share.
     - Helps to decide if a stock is overvalued or undervalued.
     - High PE Ratio indicates that the company's stock is overvalued or investors expect high growth rate.
     - Companies with no earnings or are losing money don't have a P/E ratio because there's nothing to put in the denominator.
     
   - Beta (Measure of Volatality):
     - Measure of volatality (systematic risk) of a security or portfolio compared to the market as a whole.
     - Beta is used in Capital Asset Pricing Model (CAPM) which describes the relationship between systematic risk and expected return on asset.
     - Beta coefficient = Covarience(Return of individual stock, return of market) / Variance(Return of market)
     - S&P500 has a beta of 1
    
    - Correlation:
      - Negative correlations may help diversify risk, while positive correlations could indicate co-movement in prices.

3. 