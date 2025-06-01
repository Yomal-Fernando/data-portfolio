# Personal Expense Log – Pivot & Chart (Day 2)

**Objective**  
Summarise one month of dummy transactions to understand spending habits.

## Dataset  
*15 synthetic rows* created on Day 1 (see `expense_log_day1.xlsx`).

## Method  
1. Added helper column `Month` (`=TEXT(Date,"yyyy-mm")`).  
2. Built pivot-table “Spend by Category” (rows = Category, values = SUM Amount).  
3. Created second pivot for monthly net cash-flow.  
4. Inserted bar chart to visualise category totals.  
5. Applied conditional formatting to highlight positive vs negative cash flow.

## Key findings  
* Groceries (–$318) and Fuel (–$206) are my top expenses.  
* Salary + freelance income = $3 850; net cash flow $1 072 (surplus).  
* Entertainment spend is modest (–$25), suggesting room for leisure budget.

## Next steps  
* Load real 3-month bank CSV.  
* Add sparklines for weekly trend.  
* Compare % of income spent on fixed costs (Rent, Utilities) vs discretionary.
