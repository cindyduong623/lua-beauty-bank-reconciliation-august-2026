# Lụa Beauty: Bank Reconciliation (August 2026)
Month-End Bank Reconciliation for Fictional Vietnamese Beauty Brand

## About This Project
A month-end bank reconciliation for Lụa Beauty's operating checking account, comparing the bank statement against the company's general ledger and resolving the differences between them.

## Process
Started with two raw exports: a bank statement and a general ledger, each with inconsistent date formats. After cleaning both, I compared them line by line to identify six reconciling items:

- Two outstanding checks (#2205, #2206) written and recorded in the GL, not yet cleared by the bank
- One deposit in transit (Orchid Lane Boutique) recorded in the GL, not yet reflected on the bank statement
- Interest earned and a monthly service charge: bank-initiated, not yet recorded in the GL
- One NSF (bounced) customer payment reversed by the bank, not yet reflected in the GL
- One data entry error: a check was recorded in the GL at $90 less than its actual amount

## Result
Both the adjusted bank balance and adjusted book balance reconcile to $7,339.98.

## Follow-Up Items:
- Contact Jade Row Cosmetics regarding NSF returned payment ($6,407.70).
- Correct Check #2202 entry in accounting system.

## Files
- `Lua_Beauty_Bank_Reconciliation.xlsx`: Excel workbook (README, Bank Statement, General Ledger, Reconciliation)
