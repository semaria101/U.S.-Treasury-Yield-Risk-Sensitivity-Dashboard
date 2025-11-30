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

