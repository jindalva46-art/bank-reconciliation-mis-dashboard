# Bank Reconciliation, Receivables Ageing and MIS Dashboard

An Excel project for a sample distribution business (April to September 2026). It reconciles the cash book to the bank statement, ages receivables by customer and region, and reports sales and collections on a monthly dashboard.

## What is in the workbook
- Dashboard: month selector, sales vs collections, receivables trend, ageing, top 5 customers, regions
- Sales_Ledger and Collections: invoices, receipts, outstanding, days past due, ageing bucket
- Cash_Book and Bank_Statement: entries matched on reference
- Bank_Recon: reconciliation statement, exceptions with actions, journals to pass
- Receivables: ageing summary, customer-wise and region-wise tables, days sales outstanding
- Controls: 18 checks

## Results
- 299 cash book entries reconciled to the bank statement; the reconciliation statement closes with zero unexplained difference.
- 11 open items: 2 amount differences, 5 timing items, and 4 items found only in the bank (charges, interest, an unidentified deposit).
- Receivables outstanding: Rs 1.67 crore, of which about 36% is overdue. Days sales outstanding: about 49.
- One customer accounts for about 22% of the outstanding balance.

## Data
All data is sample data created for this project. The business, customers, invoices and bank entries are not records of a real company. The reconciling items are included on purpose to show how each type is handled.

## Tools
Excel: SUMIFS, INDEX-MATCH, SUMPRODUCT, COUNTIFS, data validation, conditional formatting, charts.
