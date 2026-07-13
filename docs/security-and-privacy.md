# Security and Privacy

## Data minimization

Only information necessary to prepare and track administrative requests should be processed. Unnecessary borrower documents and sensitive financial details should not be copied into operational notes.

## Required safeguards

- Client-owned accounts and credentials
- Least-privilege Airtable, Gmail, and automation permissions
- Secrets stored outside source control
- Test and production separation
- Human approval before sending
- Recipient verification
- Audit fields for status, errors, and draft identifiers
- Prompt-injection resistance when processing external email or documents

## Prohibited repository content

- Borrower names and contact information
- Real property addresses and loan numbers
- Loan documents or financial records
- API keys, passwords, OAuth secrets, and tokens
- Airtable invite links or Zapier editor links
- Client-specific private procedures

## Compliance boundary

This technical workflow is not represented as legally compliant merely because safeguards exist. The deploying organization remains responsible for legal, regulatory, security, privacy, record-retention, and vendor-risk review.

