# REST API Learning

Hands-on practice with REST APIs and OpenAPI. Each file is a small, self-written API description that I built step by step while learning.

## Samples

| File | What it describes |
|------|-------------------|
| `auction-api.yaml` | Auction API: auction detail, filtered list, placing a bid (`POST` with 201/400/404/422 responses) |
| `reviews-api.yaml` | Reviews API: review detail, list with optional `min_rating` filter, reusable `Review` schema |

Both files are valid OpenAPI 3.0.3 and can be pasted into [editor.swagger.io](https://editor.swagger.io).

## What I practised

- HTTP methods (GET, POST, PUT, PATCH, DELETE) and status codes (2xx, 4xx, 5xx)
- Path, query and body parameters
- Authentication vs authorization (401 vs 403, API key, Bearer token, OAuth 2.0)
- OpenAPI structure: `paths`, `parameters`, `requestBody`, `responses`
- Reusable schemas with `components` and `$ref`
- Required vs optional vs nullable fields
- Testing real APIs in Postman

## Next steps

- [ ] Pagination, a unified error format, versioning
- [ ] Idempotency, rate limiting (429), asynchronous calls (202, webhooks)
- [ ] API design and naming conventions
- [ ] API testing and mocking
- [ ] SQL basics

## Note

All examples are fictional and created for learning purposes only.
