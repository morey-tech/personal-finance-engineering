# Personal Finance Engineering
Collection of APIs that manage my personal finances.

## Account Transactions
Requirements:
- Take in bank account transaction file
- Store transactions in a local database.
  - Consider using YNAB transaction schema.
- Upload to YNAB.
  - https://api.ynab.com/v1#/Transactions/createTransaction
  - Some transaction files will need transformation (e.g. EQ Bank).

Outcome, upload all previous transactions to YNAB to build a complete history of my spending.

Future outcome is to auto update net-worth.