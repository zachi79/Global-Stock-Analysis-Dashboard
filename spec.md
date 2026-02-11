# Project Specification: Global Stock Insight Dashboard (Professional Version)

## 1. Project Goal
An English-language web application providing a deep-dive analysis of stocks from S&P 500, TA-125, Nikkei 225, and European markets. The focus is on fundamental health, efficiency metrics, and AI-driven qualitative insights.

## 2. Core Indices Support
* **USA:** S&P 500 | **Israel:** TA-125 | **Japan:** Nikkei 225 | **Europe:** Major exchanges.

## 3. Detailed Feature Requirements

### A. Qualitative Analysis (AI Powered via GPT-4o/Claude)
1. **Business Profile:** Sector, core products, and Competitive Advantage (Moat).
2. **Management:** Key executives and brief backgrounds.
3. **Strategic Vision:** Long-term goals and SWOT Analysis (Strengths, Weaknesses, Opportunities, Threats).
4. **Competitors:** Main global and local rivals.

### B. Financials & Valuation (Latest Updated Data)
5. **Core Metrics:** P/E Ratio, PEG Ratio, EPS (Earnings Per Share).
6. **Efficiency:** ROE (Return on Equity) and Revenue Growth (YoY).
7. **Financial Health:** Current Ratio, Debt-to-Equity, and Free Cash Flow (FCF).
8. **Market Context:** Market Cap, 52-Week High/Low, and Beta (Volatility).
9. **Dividends:** Yield and payout history.

### C. Visualizations & News
10. **Historical Charts:** 1D, 1W, 1M, 6M, 1Y, 3Y, 5Y.
11. **Analyst Consensus:** Buy/Hold/Sell percentage and target prices.
12. **English News Summary:** Latest headlines with sentiment analysis.

## 4. Technical Requirements
* **Language:** Entire UI/Logic in English. 
* **Tooltips:** Provide short Hebrew explanations for each financial metric (content provided in project docs).
* **Framework:** Next.js (App Router), Tailwind CSS, Shadcn/UI.
* **API:** Yahoo Finance (via `yahoo-finance2` or similar).