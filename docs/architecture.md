# Architecture

## Components

1. **Input layer**: authorized staff enter or extract loan information.
2. **Airtable**: stores orders, lender relationships, operational status, deadlines, and automation state.
3. **Deterministic clause logic**: order type selects the title clause, insurance clause, or both.
4. **Template layer**: generates a proposed subject and message from structured fields.
5. **Human approval**: staff confirm the recipient, clause, loan data, and requested documents.
6. **Zapier**: creates a Gmail draft and writes the resulting draft identifier back to Airtable.
7. **Follow-up controls**: Airtable views surface missing items, overdue dates, vendor ETAs, and priorities.

## Important states

- `Intake`
- `Needs Review`
- `Approved for Test Draft`
- `Draft Created`
- `Failed`
- `Manual Review`

## Reliability controls

- Stable Airtable record identifiers
- Required-field validation
- Manual review for missing clauses
- Test environment marker
- Draft-created checkbox and draft ID for deduplication
- Error field for automation failures
- Human review before sending

## Boundaries

The workflow provides administrative support only. It does not make underwriting, eligibility, pricing, compliance, or fair-lending determinations.

