# U.S.-Treasury-Yield-Risk-Sensitivity-Dashboard
A macro–fixed income analysis project with direct applications in Portfolio Management and Venture Capital / Private Markets.
📈 Overview

This project analyzes historical movements in the U.S. 10-Year Treasury Yield and models how changes in long-term interest rates impact the price of a 10-year bond. It also connects interest-rate cycles to private-market investing: startup valuations, venture debt costs, and private equity financing structures.

The dashboard provides a clear, visual, and practical understanding of how macro interest-rate conditions influence both public-market portfolio management and private-market investment dynamics.

🔍 Key Features
1️⃣ Historical Yield Trend Analysis

Visualizes weekly 10-Year Treasury yields over time

Highlights rate cycles and macroeconomic shifts

Includes summary statistics such as:

Average yield

Minimum & maximum yields

Yield volatility (standard deviation)

2️⃣ Interest-Rate Sensitivity Modeling

Using a simplified duration-based model, the dashboard estimates the price impact of rate changes on a 10-year Treasury-like bond.

Assumptions used:

Par Value: 100

Coupon: 4%

Modified Duration: 8

Scenario Results:

+1% yield increase → approx. –8% price decline

–1% yield decrease → approx. +8% price gain

+2% yield increase → approx. –16%

–2% yield decrease → approx. +16%

This demonstrates the core fixed-income principle:
When yields rise, bond prices fall — and long-duration bonds move the most.

3️⃣ Relevance to Venture Capital & Private Markets

Although Treasury yields come from public fixed-income markets, they directly influence private-market investing:

Higher yields → higher discount rates → lower startup valuations

Higher yields → more expensive venture debt → shorter runway

Higher yields → tighter liquidity & higher financing risk

PE/LBO deals become more expensive due to increased interest costs

Lower yields → cheaper capital → higher valuations & more deal activity

This project shows the connection between macro rate environments and the pricing, risk, and capital structure dynamics in VC, growth equity, and private equity.

🗂 Project Structure
📁 UST-Yield-Sensitivity-Dashboard/
│
├── 1_RawData
│   • Cleaned 10-Year Treasury data (Date, Yield)
│
├── 2_Yield_Chart
│   • Time-series yield chart + summary statistics
│
├── 3_Risk_Sensitivity
│   • Duration-based sensitivity model (+/- rate scenarios)
│
└── README.md

🧠 Methodology
Data Source

Federal Reserve Economic Data (FRED)
Series: WGS10YR — Market Yield on U.S. Treasury Securities at 10-Year Constant Maturity

Pricing Approach

This project uses the standard duration approximation:

ΔP ≈ –D × Δy


Where:

D = Modified Duration (8)

Δy = Yield change

This is the same first-order risk measure used by fixed-income portfolio managers, risk teams, and institutional investors.

🎯 Why This Project Matters
For Portfolio Management

Shows how bond prices react to interest-rate changes

Demonstrates duration-driven risk

Provides tools for positioning and scenario analysis

For Venture Capital & Private Markets

Treasury yields anchor valuation discount rates

Higher yields compress valuations and raise hurdle rates

Venture debt becomes more expensive → shorter cash runway

PE financing becomes more constrained due to higher cost of debt

Understanding yield movements is critical for investors evaluating valuation, capital structure, runway, and financing risk.

▶️ How to Use the Dashboard

Open the Excel workbook.

Explore the RawData tab to review the historical yield inputs.

View the Yield Chart tab to understand rate trends and summary metrics.

Adjust the Base Yield in the Risk_Sensitivity tab to run new scenarios.

Review how rate changes affect bond prices and financing implications.

🚀 Future Improvements

Build a full yield curve (2Y/5Y/10Y/30Y) comparison

Add corporate and municipal bond spread dashboards

Create a startup runway sensitivity model linked to yields

Add a private equity LBO rate-sensitivity module

Convert the dashboard into a Python/FRED API version
