# Demonstration Walkthrough

## Intended length

Two to three minutes.

## Recording safety

Use the fictional records in this repository or a dedicated demonstration base. Do not display browser tabs, notifications, URLs, account menus, real names, live loan numbers, email addresses, API credentials, or client records.

## Script

### 1. Introduce the business problem

> Mortgage operations teams repeatedly collect loan information, locate the correct lender clause, prepare title or insurance requests, and monitor missing items. This workflow organizes those steps while keeping a person in control of every outbound message.

### 2. Show the fictional order

Display `DEMO-001 - Title` and identify:

- Borrower
- Property
- Loan number
- Transaction type
- Lender
- Order type
- Follow-up owner

### 3. Show clause selection

> Selecting the lender and order type retrieves the corresponding title or insurance clause. If the required clause is unavailable, the record moves to manual review instead of producing an unverified request.

### 4. Show the approval gate

> A staff member checks the recipient and populated fields, then marks the record approved for a test draft. The system does not automatically send the message.

### 5. Show draft creation

Display the sanitized email-draft mockup.

> Zapier creates a Gmail draft and writes the draft identifier back to Airtable. That writeback prevents the same record from remaining eligible for another draft.

### 6. Show operational views

Display the sanitized dashboard mockup.

> Dedicated views identify overdue follow-ups, missing items, expired vendor ETAs, and high-priority records. A daily digest summarizes actionable items for the operations owner.

### 7. Close with boundaries

> This is an administrative workflow-support system. It does not approve loans, underwrite loans, determine eligibility, or replace qualified compliance review. Outbound messages remain human-reviewed.

