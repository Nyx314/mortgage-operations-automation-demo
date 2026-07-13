# User Guide

## Create a test draft

1. Add or review the order in Airtable.
2. Complete the borrower, property, loan number, transaction type, lender, order type, and recipient fields.
3. Confirm `Clause Review Status` is `READY`.
4. Set `Environment` to `Test`.
5. Set `Workflow Status` to `Approved for Test Draft`.
6. Wait for Zapier polling or run the Zap manually.
7. Confirm the record changes to `Draft Created` and receives an email draft ID.
8. Open Gmail **Drafts** and review the message.

The Airtable approval view is a waiting queue. A processed record leaves that view after the draft is created.

## Review before sending

- Recipient
- Borrower
- Property
- Loan number
- Lender
- Mortgagee clause
- Order type
- Requested documents
- Closing date and amounts, when present

Never send a record marked `MANUAL REVIEW`.

