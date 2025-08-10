# 2024 Retail Operating Efficiency Analysis

## Project Overview

This analysis evaluates the operational efficiency of major U.S. retail companies in 2024 by examining accounts receivable turnover, inventory turnover, and accounts payable turnover. It calculates and compares each company's Operating Cycle and Cash Conversion Cycle (CCC) to reveal differences in working capital management, supply chain efficiency, and cash flow strategy.

### Key Metrics

- **DSO (Days Sales Outstanding):** Average number of days to collect payment after a sale; lower values indicate faster collections.  
- **DOH (Days of Inventory on Hand):** Average number of days inventory is held before being sold; lower values indicate faster inventory turnover.  
- **DPO (Days Payable Outstanding):** Average number of days to pay suppliers; higher values indicate slower cash outflow.  
- **Operating Cycle = DSO + DOH:** Measures total time from investment in inventory to cash collection.  
- **Cash Conversion Cycle (CCC) = Operating Cycle – DPO:** Measures the net time cash is tied up in operations; shorter (or negative) values indicate stronger liquidity.

### Key Findings

- **Negative CCC Leaders:**  
  Wayfair (-42.66 days) and Amazon (-35.56 days) extend DPO significantly (54.95 days and 105.56 days respectively), meaning they can collect from customers before paying suppliers—effectively funding operations with supplier capital. This model is typical for platform-based or cash flow–optimized e-commerce businesses.  

- **High CCC Companies:**  
  Ulta (70.84 days) and Macy’s (48.13 days) have longer cash tie-up periods, largely due to slow inventory turnover (DOH = 93.15 days for Ulta, 111.91 days for Macy’s), creating higher working capital demands.  

- **Industry Median Performance:**  
  Large brick-and-mortar retailers like Walmart, Target, and Costco maintain CCC in the 0–10 day range, showing balanced supply chain and cash flow management.  

- **Extreme Inventory Strategies:**  
  Wayfair holds minimal inventory (DOH = 3.35 days), relying heavily on supplier drop-shipping. Macy’s holds inventory over 111 days, likely driven by seasonal merchandise and department store product mix.

### Business Implications

- **Negative CCC Advantage:** Enables growth or reinvestment using supplier capital but requires strong supplier negotiation power.  
- **Inventory Risk:** High DOH increases cash lock-up and the risk of obsolescence, requiring tighter inventory management.  
- **Receivables & Payables Strategy:** Coordinating DSO and DPO effectively can significantly improve CCC and liquidity.

---

## Project Details

This mini project uses Python to fetch financial data via Yahoo Finance (`yfinance`), calculate key efficiency ratios, and visualize the results using Matplotlib.

### How to Run

1. Clone or download this repository.  
2. Ensure you have Python 3 installed with the following packages:pandas, yfinance and matplotlib
