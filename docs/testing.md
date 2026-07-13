# Testing

## Verified controlled scenarios

| Scenario | Expected result | Status |
| --- | --- | --- |
| Approved lender selected for title order | Title clause populates | Passed |
| Approved lender selected for insurance order | Insurance clause populates | Passed |
| Missing clause | Record routes to manual review | Passed |
| Title request | Title-specific subject and body generate | Passed |
| Insurance request | Insurance-specific subject and body generate | Passed |
| Approved test record | Gmail draft is created | Passed |
| Successful draft | Airtable receives draft ID and status | Passed |
| Zap runs again | Existing record does not create another eligible draft | Passed |
| Overdue follow-up | Record appears in overdue view | Passed |
| Missing item | Record appears in missing-items view | Passed |
| Vendor ETA has passed | Record appears in vendor-ETA view | Passed |
| High priority | Record appears in priority view | Passed |
| Scheduled digest | Notification reaches the test recipient | Passed |

## Still required for each deployment

- Client-specific real-loan pilot with outbound messages held as drafts
- Broker approval of title and insurance request language
- Authentication-expiration test
- Incorrect-recipient prevention test
- Duplicate source-event test
- Recovery test for Zapier, Gmail, or Airtable failure
- Client acceptance and training

