# Jaiprakash Power Ventures Ltd. (JP Power) — Equity Valuation & Financial Model

A bottom-up financial model and valuation analysis of Jaiprakash Power Ventures Ltd. built in Microsoft Excel to evaluate post-turnaround fundamentals and intrinsic equity value.

## 📈 Key Valuation Outputs

- **Intrinsic Value (DCF Base Case):** ₹5.75 per share
- **Current Market Price (CMP):** ₹13.40 per share
- **Market Status:** Overvalued by **2.33x** relative to core intrinsic cash-flow value
- **Weighted Average Cost of Capital (WACC):** 12.85%
- **Terminal Growth Rate:** 4.50%
- **Organic Expected Growth Rate:** 1.72%

---

## 🏢 Project Overview & Turnaround Context

Jaiprakash Power Ventures Ltd. presents a classic post-restructuring turnaround story in the Indian power sector. This model evaluates whether the market price reflects fundamental cash-flow performance after aggressive debt clean-up and operational stabilization.

---

## ⚙️ Core Modules & Methodology

### 1. Historical Financial Statements (FY17 – FY26)
- Integrated Income Statement, Balance Sheet, and Cash Flow Statement with dynamic reconciliation checks (`Total Assets = Total Liabilities + Equity`).
- Tracks aggressive debt restructuring, showing total borrowings reduced from **₹23,994 Cr** (FY17) down to **₹3,391 Cr** (FY26) alongside cash reserves scaling to **₹2,008 Cr**.

### 2. Ratio & Solvency Analysis
- Evaluates operational efficiency, margin stability, and earnings quality across 10 historical years.
- Captures solvency recovery (Interest Coverage improving from **0.34x** to a peak of **3.94x**) and working capital dynamics (negative Cash Conversion Cycle driven by extended supplier payable days).

### 3. Statistical Forecasting (Linear Regression)
- Programmed 10-year Excel linear regression (`SLOPE` and `INTERCEPT`) using numerical year weights to project top-line revenue and EBITDA baseline trends through FY31E without arbitrary assumptions.

### 4. Cost of Capital & Beta Estimation
- Calculated 2-year weekly return regressions (**104 observations**) against the NIFTY 50 index and applied Blume’s adjustment to raw betas.
- Unlevered betas across 5 Indian power sector peers (NTPC, Adani Green, JSW Energy, NHPC, NLC India) to isolate a median asset beta of **0.57**, re-levered to JP Power’s **85.19%** target Debt/Equity structure (**0.93** levered beta).
- Derived a **15.93%** Cost of Equity (Risk-Free Rate: 7.31%, Equity Risk Premium: 9.23%) and **9.23%** After-Tax Cost of Debt, resulting in an institutional **12.85% WACC**.

### 5. Fundamental Growth & DCF Valuation
- Computed organic growth (**1.72%**) by multiplying historical Return on Invested Capital (ROIC ~5%) by the reinvestment rate (~21%).
- Projected Free Cash Flows to Firm (FCFF) through FY32F using a mid-year discounting convention and Gordon Growth terminal value calculation.
- Included a two-way sensitivity matrix across WACC and terminal growth rates.

### 6. Relative Comps & Football Field Analysis
- Benchmarked JP Power against peer trading multiples (Median EV/EBITDA: **6.89x**, Median P/E: **15.01x**).
- Synthesized Bear, Base, and Bull DCF scenarios alongside relative peer multiples and 52-week trading ranges (**₹12.50 – ₹24.50**) into a professional Football Field chart.

---

## 🛠️ Tech Stack & Tools

- **Tool:** Microsoft Excel (Financial Modeling, Data Analysis ToolPak, Dynamic Arrays, Floating Bar Charts)
- **Core Methodologies:** 3-Statement Modeling, DCF (FCFF), CAPM, Peer Beta Unlevering, Linear Regression, Relative Multiples, Sensitivity Analysis
