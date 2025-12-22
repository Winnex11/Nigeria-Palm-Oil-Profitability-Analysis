# Nigeria Palm Oil Profitability Analysis  
### Investment Feasibility Study for ₦1 Billion Annual Profit

## Project Overview
This project evaluates the financial feasibility of establishing a large-scale palm oil plantation in Nigeria capable of generating **₦1 billion in annual profit**. Using publicly available data, industry benchmarks, and proxy cost estimates, a profitability model was developed to assess yields, costs, returns, and investment risks across major palm oil–producing states.

The analysis is designed to answer a real-world investor question:

**“At what scale and in which Nigerian states will a palm oil plantation generate ₦1 billion in annual profit?”**

## Objectives
The key objectives of this study were to:
- Estimate **profit per hectare by state**
- Determine the **plantation size required** to achieve ₦1 billion annual profit
- Calculate **total investment requirements**
- Evaluate **NPV, IRR, ROI, and payback period**
- Compare states under **Conservative, Base, and Optimistic scenarios**
- Provide **clear, data-driven investment recommendations**

## Data Sources
Data was compiled from multiple credible sources:

### Industry Benchmarks
- Presco PLC Annual Reports
- Okomu Oil Palm PLC Annual Reports

### Agricultural & Production Data
- FAOSTAT (1990–2023 palm oil production, yield, and area)
- Nigerian Institute for Oil Palm Research (NIFOR)
- PIND Foundation (regional yield variations)

### Market & Cost Proxies
- Nigerian crude palm oil (CPO) market prices
- PropertyPro Nigeria (land cost estimates)
- Jiji Nigeria (equipment and machinery pricing)

### Climate & Suitability
- World Bank Climate Knowledge Portal
- FAO Soil and Climate resources

All sources are documented and assumptions are clearly stated in the report.

## Tools Used
- Python (Pandas, NumPy)
- Microsoft Excel
- Power BI
- Jupyter Notebook

## Methodology Summary

### Data Preparation
- Cleaned and reshaped FAOSTAT data
- Standardized all units (hectares, tonnes, ₦)
- Extracted benchmarks from company reports
- Merged climate, yield, cost, and price data

### Profitability Modeling
Revenue per hectare was calculated using:
- Fresh Fruit Bunch (FFB) yield per hectare
- Industry-standard CPO extraction rate (21%)
- State-level yield variations
- Market-based CPO pricing

Costs were divided into:
- **Operating Costs (OPEX):** fertilizer, labor, maintenance, overhead
- **Capital Costs (CAPEX):** land acquisition, planting, seedlings, processing mill

### Financial Metrics Computed
- Net Profit per hectare
- Required plantation size for ₦1bn profit
- Net Present Value (NPV)
- Internal Rate of Return (IRR)
- Return on Investment (ROI)
- Payback period

### Scenario Analysis
Three scenarios were modeled:
- **Conservative:** low yield, lower prices, higher costs
- **Base Case:** realistic commercial assumptions
- **Optimistic:** improved yields and favorable pricing

## Key Findings
- **Edo State** is the most profitable location, generating approximately **₦12.1 million profit per hectare annually**
- Achieving ₦1 billion annual profit in Edo State requires **8,559 hectares** and **₦20.77 billion** total investment
- Base case financial performance:
  - **NPV:** ₦65.6 billion
  - **IRR:** 17.3%
  - **ROI:** 107.6%
  - **Payback Period:** ~4.2 years
- Even under conservative assumptions, returns remain above the 12% investment hurdle rate
- Crude Palm Oil (CPO) price is the single most sensitive risk factor

## Top States by Profitability
1. **Edo State** – ₦12.1M profit/ha
2. **Akwa Ibom State** – ₦11.4M profit/ha
3. **Cross River State** – ₦11.4M profit/ha

## Business Recommendation
Proceed with a phased investment in **Edo State**, targeting an **8,559-hectare plantation**, supported by:
- Long-term supply contracts to manage price risk
- NIFOR-certified seedlings to protect yields
- Phased land development to reduce upfront capital pressure

## Limitations
- Analysis relies on proxy data and publicly available benchmarks
- Market prices are subject to volatility
- Operational execution quality significantly affects outcomes

## Future Work
- Incorporate live commodity pricing feeds
- Extend analysis to additional states
- Build a fully interactive geospatial investment dashboard
- Integrate stochastic risk modeling

## Files in This Repository
- `palm_oil_profitability_analysis.ipynb` – Full analytical model
- `report/palm_oil_profitability_report.pdf` – Investor-ready report
- `Dataset/palm_oil_profitability.csv` – Dataset
- `https://app.powerbi.com/view?r=eyJrIjoiMzk5MmMxNGYtNDU0Mi00OTFjLThhN2MtYjlmYjc3ZDg5OWU1IiwidCI6Ijk2ZDcyMjUzLWY0NWItNDg1Mi1hZjRiLThiZjFkNTE3YmE3OCJ9&pageName=43d35339c783d932bdc4`– Interactive dashboard link and documentation
