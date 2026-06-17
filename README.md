# Financial-Model-and-Valuation-Model-of-TCS

# TCS Valuation & Financial Model

A ground-up DCF valuation and financial model for Tata Consultancy Services (TCS).

**Implied share price: ₹2,337** (base case)

## What's Inside

- **Financial Model** — 5 years of historical financials (FY2020–FY2024) restructured into a clean, color-coded model, with projection assumptions derived from historical trends.
- **DCF Valuation** — FCFF projected through FY2029, discounted at a bottom-up WACC (~12.6%), with terminal value via Gordon Growth.
- **Sensitivity Analysis** — Implied price across a range of WACC (11.5%–14.0%) and terminal growth (4.5%–7.0%) assumptions.

# Methodology

- **WACC**: CAPM-based cost of equity (Rf from 10-yr GOI bonds, ERP from Damodaran, beta from 2-yr regression vs. Nifty 50), blended with near-zero cost of debt given TCS's debt-free balance sheet.
- **FCFF**: Built from EBIT → NOPAT, adjusted for D&A, capex, and working capital changes.
- **Terminal Value**: Gordon Growth at 6% long-run growth, discounted back 5 years.
- **Equity Bridge**: EV adjusted for cash, investments, lease liabilities, and minority interest, divided by shares outstanding.

## Results

| Scenario | WACC | Terminal Growth | Implied Price |
|---|---|---|---|
| Bear | 14.0% | 4.5% | ~₹1,723 |
| Base | 12.6% | 6.0% | **₹2,337** |
| Bull | 11.5% | 7.0% | ~₹3,259 |

DCF value sits at a premium to comps, consistent with TCS's strong FCF generation, near-zero debt, and capital-light model.

## Tools

Built in Excel. Assumptions sourced from TCS annual reports, NSE filings, RBI data, and Damodaran's India risk premium estimates.

