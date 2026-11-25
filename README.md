# Bank Loan Analysis & Risk Assessment

## What
An analysis of 38,576 bank loan applications (24 columns) to track lending performance and separate good loans from bad loans. It reports the key lending KPIs a bank team watches: applications, funded amount, amount received, interest rate and debt-to-income ratio.

## How
- **Data:** loan dataset (`financial_loan_1.csv`), 38,576 records, with issue, payment and credit-pull dates converted to datetime.
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly (Jupyter Notebook).
- **Approach:**
  1. Inspected the data (shape, data types, summary statistics) and fixed date columns.
  2. Calculated KPIs with month-to-date (MTD) views: total applications, total funded amount, total amount received, average interest rate, average DTI.
  3. Split loans into good loans (Fully Paid, Current) and bad loans (Charged Off).
  4. Built charts for monthly trends and breakdowns by state, loan term, employment length, loan purpose and home ownership.

## Impact / Results
- 38,576 applications; $435.76M funded; $473.07M received.
- Average interest rate 12.05%; average DTI 13.33%.
- Good loans: 33,243 applications (86.18%). Bad loans: 5,333 applications (13.82%), $65.53M funded and $37.28M recovered.
- Gives a lender a clear view of lending trends and where risk is concentrated.

## Files
- `Bank_Loan_Data.ipynb`: full analysis notebook.
