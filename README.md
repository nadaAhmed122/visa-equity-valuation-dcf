# Visa Inc. Intrinsic Equity Valuation (DCF) | 2020–2024

This project implements a full FCFF-based Discounted Cash Flow (DCF) valuation model for Visa Inc., integrating profitability decomposition and ESG risk considerations into intrinsic value estimation.

---

## Modelling Framework

The valuation model links operating performance directly to shareholder profitability through an enhanced DuPont decomposition:

ROE = Net Profit Margin × Asset Turnover × Equity Multiplier × Cash Conversion Ratio

The inclusion of a cash conversion factor allows accounting profitability to be adjusted for earnings quality, ensuring internal consistency with forecasted free cash flows used in enterprise valuation.

Intrinsic firm value is estimated using:

- FCFF Forecasting (2025–2029)
- CAPM-derived Cost of Equity
- Weighted Average Cost of Capital (WACC)
- Terminal Value (Gordon Growth Method)

---

## Valuation Results

| Parameter | Base Case |
|----------|-----------|
Intrinsic Value | **$22**
