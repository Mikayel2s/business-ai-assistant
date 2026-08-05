feat(v1.0.0): complete Orion Gateway and Atlas Search API

Phase 1 completed.

Features
- Orion API Gateway
- Atlas Search API
- AI Search Planner
- PostgreSQL integration
- OpenAI Responses API
- Quotations
- Invoices
- Receipts
- Transport Requests
- Pagination
- Analytics
- Shared API Response
- Shared No Results Response
- Production webhooks
- Postman integration

Hardening
- Unified No Results handling
- SQL Always Output Data configuration
- IF routing for empty result sets
- Removed duplicated No Results logic
- Production response architecture

Validated
- Existing quotation retrieval
- Existing invoice retrieval
- Existing receipt retrieval
- Existing transport retrieval
- Graceful no-result responses
- End-to-end Orion ↔ Atlas communication

Release
v1.0.0