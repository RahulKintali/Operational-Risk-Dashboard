This Power BI dashboard provides insights into operational loss incidents by tracking key risk metrics.

Key Tasks Performed:
ETL is performed on original Dataset. Steps included in ETL:
  a)Data Extraction - Identified key attributes such as `Transaction_ID`, `Date`, `Amount`, `Category`, `Payment_Method`, and `Risk_Incident`.
  b)Data Cleaning   - Handled Missing Values, Standardized Data Types, Removed Duplicates
  c)Data Transformation - Created New Columns like `Risk_Percentage` based on `Risk_Incident` transactions.
                        - Filtered High-Risk Transactions based on `Risk_Incident = 1` value.
Lastly Exported Cleansed Dataset for Power BI analysis.

Power BI Dashboard Features

✅ KPIs: Total Transactions, High-Risk Transactions, Risk Percentage  
✅ Visuals: Line Charts, Pie Charts, Bar Graphs  
✅ Interactive Filters: Date, Category, Payment Method  
✅ Conditional Formatting for Risk Levels  

Key Inferences from Dashboard:
1️⃣ High-Risk Transactions → Concentrated in specific counterparties & financial/payroll categories.  
2️⃣ Risk Trends → Spikes in system failures & fraud during certain months.  
3️⃣ Payment Methods → Bank transfers & cash have higher risk; credit cards show lower fraud rates.  
4️⃣ Category Risks → Sales & marketing have moderate risk; inventory transactions are low-risk.  
5️⃣ Risk Management → Strengthening fraud detection & enforcing compliance can mitigate high-risk areas.  
