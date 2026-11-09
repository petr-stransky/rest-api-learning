# REST API Learning

Notes and exercises from my self-study of REST APIs, written from a business analyst's point of view.

## What is in this repository

- `auction-api.yaml`: an OpenAPI 3.0 specification of a simple, fictional Auction API with three operations:
  - `GET /auctions/{id}`: auction detail
  - `GET /auctions`: list of auctions with `status` and `limit` query parameters
  - `POST /auctions/{id}/bids`: place a bid, with request body validation and error responses (`201`, `400`, `404`, `422`)

## What I practised

- HTTP methods, status codes and the difference between `401` and `403`, `400` and `422`
- Path parameters, query parameters, headers and request bodies
- Reading and writing OpenAPI specifications (YAML), including required fields and enums
- Testing public APIs in Postman

## How to view the specification

Paste the contents of `auction-api.yaml` into [Swagger Editor](https://editor.swagger.io) to see the rendered documentation.

## Next steps

- Nested objects and reusable schemas (`$ref`)
- Pagination, versioning and error format conventions
- SQL for data analysis
