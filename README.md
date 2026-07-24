# README: Projected Financial Model (2026E-2030E) The Kraft Heinz Company (KHC)
*Read this in [Spanish](KHC_Financial_Model_2026E-2030E_README_ES.md)*

## 1. Introduction and Scope
This document describes the structure, key projection assumptions (drivers), and main insights of the three-statement financial model for The Kraft Heinz Company (KHC). This model was developed in Excel with AI technical support, using the [Annual Report Form 10-K 2025](KHC_Annual_Report_10K_2025.pdf) submitted to the SEC as the single source of historical data for the 2023A-2025A period. Its purpose is to project the company's financial statements for five years (2026E-2030E), complying with financial standards and ensuring a perfectly balanced balance sheet.

[📥 **Download the Financial Model in Excel**](https://github.com/jeansebastiannino/KHC-Financial-Model/raw/refs/heads/main/KHC_Integrated_Financial_Model_2026E-2030E.xlsx)

### Model Previews

![Income Statement](IS_preview.png)

![Balance Sheet](BS_preview.png)

![Cash Flow Statement](CF_preview.png)

## 2. Model Structure
An integrated three-statement financial model was implemented, structured through logical Schedules and driver-based to project future performance based on historical trends, efficiency metrics, regulatory parameters, and normalization adjustments:

* **Schedules:** Contains the operational (Net Sales, Cost of Products Sold, OpEx, Net Working Capital), capital, financing and tax (CapEx, D&A & PP&E, Debt & Interest, Tax Rate), and accounting reconciliation (Retained Earnings, Other Cash Flow Items, Restricted Cash) modules.
* **Income Statement:** Projects profitability (from Net Sales to Net Income) by consolidating the impacts of the operational and financial schedules.
* **Balance Sheet:** Reflects the financial position (assets, liabilities, and equity) integrating a dynamic balancing control (Balance Check).
* **Cash Flow Statement:** Reconciles net income with actual cash generation using the indirect method, isolating non-cash items and capital requirements.

## 3. Key Projection Assumptions (Drivers)

* **Net Sales:** Revenue projection by segment based on annual net sales growth. For the North America segment, a flat growth (0.0%) was set to avoid dragging the atypical contraction of the last year (-4.90%). For the International Developed Markets (0.11%) and Emerging Markets (1.77%) segments, the last historical rate was projected, as their values are consistent with the natural growth rate of each market.
* **Cost of Products Sold:** Direct cost (COGS) projected by segment as a percentage of sales. The last historical rate (66.69%) is applied to reflect the company's current direct cost structure, considering the impact of the inflationary pressure observed in 2025A and maintaining a conservative stance given the projected uncertainty for the 2026E fiscal year (p. 28 of the 10-K).
* **OpEx:** Projected as a percentage of sales, the last historical rate (14.72%) is used to maintain the company's current operating expense structure, ensuring consistency between the stabilization of projected net revenues and operating income.
* **Net Working Capital:** Projection of accounts receivable (DSO: 33 days), inventories (DIO: 69 days), and accounts payable (DPO: 95 days), anchored to the last historical year to reflect the current state of the company's cash conversion cycle, in relation to inventory optimization measures and the extension of payment terms to suppliers (pp. 34 and 35 of the 10-K), as well as the increased future risk of uncollectible accounts and longer collection cycles (p. 14 of the 10-K). For its calculation, a 360-day commercial year is assumed, which averages the fiscal year-ends (52/53 weeks) by the company. Regarding prepaid expenses (1.00%) and accrued marketing (2.95%), they were projected as a percentage of sales using historical averages to link them, due to their operational nature, to the company's activity level.
* **CapEx, D&A & PP&E:** Projected as a percentage of sales, using historical averages (3.66% and 3.72% respectively) to smooth both the atypical decrease in capital expenditure and the atypical increase in its depreciation occurred in 2025A. The PP&E adds CapEx and subtracts D&A in the roll-forward to transfer the correct net balance to the Balance Sheet.
* **Debt & Interest:** For the projection of the company's total debt (current and non-current), a 100% refinancing (roll-over) is assumed in the roll-forward, given the maturity in June 2026 of $1,900M in senior notes (p. 36 of the 10-K), recording symmetrical issuances and repayments for that amount. For the rest of the period, a zero projection is recorded, maintaining a stable capital structure ($21,219M). For its breakdown on the balance sheet, the last historical rate of 8.99% corresponding to the short-term portion over total debt was kept constant. Likewise, the implied interest rate (4.61%) was kept stable to project interest expense ($978M). Accounting adjustments (FX effects and other non-cash items) were projected at zero to avoid unreal fluctuations. Interest payable (30.15%) was projected as a normalized percentage of interest expense.
* **Tax Rate:** Given the historical volatility of the effective tax rate, the U.S. statutory tax rate (21.0%) reported by the company (p. 73 of the 10-K) was used to calculate the tax provision.
* **Retained Earnings:** The projected balance in the roll-forward directly feeds the retained earnings on the Balance Sheet. Declared common stock dividends come from the historicals provided by the company in the consolidated statement of equity (p. 54 of the 10-K).
* **Other Cash Flow Items:** Secondary accounts were grouped as adjustments (historical plugs) in the historical years. Going forward, they were projected at zero, purifying the projected flow from atypical or non-operational items.
* **Restricted Cash:** The 2025A base year presented a $329M mismatch between the final balance of the Cash Flow Statement and the liquid cash of the Balance Sheet. This difference was identified as restricted cash resulting from a consolidated remaining balance of funds for the payment of employee medical benefits through trusts. This balance was recorded at the end of the fiscal year in other current (164M) and non-current (165M) assets within the consolidated financial statements (pp. 57 and 88 of the 10-K). To integrate the model, this concept was incorporated as a constant (flat) schedule from 2026E and was subtracted directly from the final flow balance, absorbing the mismatch and ensuring an exact balance check.

## 4. Base Case Insights (2026E-2030E)

* **Top-Line & Profitability:** As a result of the flat projection in North America and steady international growth, net sales reach $25,220M by 2030, reflecting a highly conservative Compound Annual Growth Rate (CAGR) of 0.22%. This top-line stabilization, combined with strategically anchored COGS, successfully consolidates a constant gross margin of 33.31%, effectively mitigating the impact of inflationary volatility recorded in prior fiscal years.
* **Operational Efficiency & Liquidity:** Disciplined maintenance of the OpEx structure (14.72%) generates strong operating leverage, securing the operating margin at 18.59%. Simultaneously, the stabilization of the cash conversion cycle (anchored to historical DSO, DIO, and DPO metrics) optimizes short-term liquidity retention. This operational efficiency allows cash and cash equivalents to significantly scale, growing from $2,615M in 2025A to a projected $7,694M by year-end 2030E.
* **Capital Allocation & Free Cash Flow:** The model demonstrates the company's ability to organically fund its capital expenditure requirements. With maintenance CapEx stabilized at a historical average of 3.66% of sales (approx. $923M annually), capital efficiency unlocks a robust and recurring Free Cash Flow (FCF), which amounts to $2,945M in the final projection year.
* **Structural Balance Sheet Health:** Assuming a full refinancing (*roll-over*) scenario that keeps gross debt steady at $21,219M, the consistent generation of net income continuously strengthens the company's equity position. Retained earnings drive Total Equity from $41,777M in 2025A to $46,821M in 2030E, progressively improving the company's long-term solvency and leverage ratios over the projected period.

---

### Disclaimer
This model is strictly for educational and portfolio demonstration purposes. It does not constitute financial advice or an investment recommendation regarding The Kraft Heinz Company (KHC). The projections are hypothetical scenarios based on public historical data. The author assumes no responsibility for the use of this material.
