# Postman API Tests

API testing project created with Postman using the DummyJSON API.

## Tools

- Postman
- JavaScript
- DummyJSON API
- GitHub

## Test Coverage

The collection includes API tests for:

- GET all products
- GET product by ID
- GET non-existing product
- POST add new product
- PUT update product
- PATCH partial update product
- DELETE product
- POST product with invalid data
- GET non-existing user

## Validations

Postman test scripts validate:

- HTTP status codes
- Response body data
- Product properties
- Error messages
- Positive and negative scenarios

## Environment

The project uses a Postman environment with the `baseUrl` variable:

`https://dummyjson.com`

Requests use:

`{{baseUrl}}`

## Project Files

- `Postman API tests.postman_collection.json` — Postman collection with requests and automated tests
- `Dummy JSON Environment.postman_environment.json` — environment variables

## How to Run

1. Import the collection into Postman.
2. Import the environment.
3. Select `Dummy JSON Environment`.
4. Run individual requests or the complete collection.
