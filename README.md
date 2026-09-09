# Fund Finance Subscription Lending - Stress Test Analysis

## Project Overview
Analysis of 15 subscription lending facilities across private credit, direct lending, and buyout funds using Python, SQL, and advanced stress testing methodologies.

## Key Findings
- **Base Case:** Portfolio leverage ranges 0.38-0.48 (healthy)
- **Downside Scenario (-15% commitments):** 0 funds in covenant breach
- **Severe Scenario (-30% commitments):** All 15 funds breach 0.60 covenant threshold
- **Highest Risk:** Blackstone BDC I (0.309 leverage increase)

## Methodology
1. **Data Collection:** 15 subscription lending facilities with LP commitments, borrowing capacity, and covenant metrics
2. **Risk Metrics Calculation:** Leverage ratios, borrowing base utilization, covenant headroom
3. **Stress Testing:** Downside (15% commitment reduction) and Severe (30% reduction) scenarios
4. **Visualization:** Professional charts showing leverage across scenarios and covenant breach analysis

## Files
- `Fund_Finance_Analysis.ipynb` - Complete Python analysis with all 5 steps
- `fund_finance_analysis.db` - SQLite database with base case, downside, and severe scenario data

## Technologies Used
- Python 3
- Pandas (data manipulation)
- Matplotlib & Seaborn (visualizations)
- SQLite (database)

## Key Metrics
- **Leverage Ratio:** Debt / LP Commitments
- **Covenant Threshold:** 0.60 (max allowed)
- **Borrowing Base:** Unfunded commitments minus 10% reserve
- **Covenant Headroom:** Buffer to covenant breach threshold

## Insights for Fund Finance
This analysis demonstrates the systemic risk in subscription lending during market stress. Even moderate LP redemptions (15-30%) can trigger covenant breaches across entire portfolios, highlighting the need for:
- Stronger LP retention strategies
- Accordion facilities for liquidity
- Reduced leverage in initial structuring
- Careful borrower selection

## Interview Talking Points
- Built stress test model for 15 subscription lending facilities
- Calculated covenant compliance under downside/severe scenarios
- Identified systemic risk: 100% portfolio breach under severe stress
- Ranked funds by risk: Blackstone BDC I highest risk (0.31 leverage increase)
- Used SQL for portfolio monitoring and scenario querying

---
**Author:** Aparna Singh  
**Date:** September 2026  
**LinkedIn:** linkedin.com/in/aparna-singh-378a73153  
**GitHub:** github.com/aparnass372
