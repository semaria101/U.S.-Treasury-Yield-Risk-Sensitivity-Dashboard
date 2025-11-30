# U.S.-Treasury-Yield-Risk-Sensitivity-Dashboard
A macro–fixed income analysis project with direct applications in Portfolio Management and Venture Capital / Private Markets.

# U.S. Treasury Yield & Risk Sensitivity Dashboard

This project analyzes historical U.S. 10-Year Treasury yields and models how changes in interest rates affect the price of a 10-year bond. It also connects interest-rate movements to valuation and financing impacts in portfolio management, venture capital, and private markets.

## Overview
- Uses weekly 10-Year Treasury yield data (FRED: WGS10YR)
- Includes a simple duration-based model to estimate how bond prices change when yields rise or fall
- Shows how macro interest-rate shifts affect:
  - Bond price volatility (Portfolio Management)
  - Startup valuations, discount rates, and venture debt costs (VC/PE)

## Features
- Cleaned historical yield dataset
- Yield trend chart with summary statistics
- Risk sensitivity model using:
  - Par value: 100
  - Coupon: 4%
  - Modified duration: 8
- Scenario results:
  - +1% yield → approx. -8% bond price change
  - -1% yield → approx. +8% bond price change

## Why It Matters
- In portfolio management: duration explains interest-rate risk and portfolio sensitivity
- In venture capital & private equity: higher yields reduce valuations and increase financing costs
- Demonstrates the link between macro conditions, valuation models, and capital structure decisions

## File Structure

project/
├── 1_RawData/
├── 2_Yield_Chart/
├── 3_Risk_Sensitivity/
└── README.md


## How to Use
1. Open the Excel workbook.
2. Review yield data in the RawData tab.
3. View the Yield_Chart tab for trends.
4. Adjust the Base Yield in the Risk_Sensitivity tab to see updated price scenarios.

## Future Improvements
- Add multiple maturity yields (2Y, 5Y, 30Y)
- Add corporate/muni spread comparison
- Add VC runway/valuation sensitivity to rates
- Build Python version using FRED API

