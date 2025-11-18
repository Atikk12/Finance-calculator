Finance Calculator - README

This application is a Tkinter-based finance calculator that allows users
to enter revenue and expense items, classify them as fixed or variable,
and automatically compute key financial metrics.

Features

-   Add revenue or expense items with amounts.
-   Mark expenses as fixed or variable.
-   Automatic calculation of:
    -   Total revenue
    -   Total fixed expenses
    -   Total variable expenses
    -   Gross profit
    -   Operating profit
    -   Taxes and net profit
    -   Margins (gross, operating, net)
-   Item list viewing and deletion.
-   Clear all items.
-   Adjustable tax rate.
-   Export financial summary to a .txt file.
-   Preloaded sample items on startup.

How to Use

1.  Run financecalculator.py.
2.  Enter an item name and amount.
3.  Select whether it is a revenue or expense item.
4.  If it is an expense, optionally mark it as variable.
5.  Add the item using the Add Item button.
6.  View computed financial summaries in the bottom panel.
7.  Adjust tax rate and recalculate when needed.
8.  Export summary using the Export Summary button.

Requirements

-   Python 3.x
-   Tkinter (comes bundled with most Python installations)

Running the Application

    python financecalculator.py

Notes

-   Invalid numerical inputs default to 0.
-   Negative tax rates are not allowed.
-   The UI loads with sample items for demonstration.
