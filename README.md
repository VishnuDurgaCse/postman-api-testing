# E-Commerce API Testing — Postman Collection

A Postman collection testing a complete e-commerce API flow 
with token-based authentication, request chaining, 
and JavaScript assertions.

## What This Project Covers

- Login with Bearer token authentication
- Auto token save and reuse across all requests
- Chained requests using collection variables
- Pre-request validation scripts
- JavaScript assertions on responses

## API Flow

1. Login → Bearer token auto saved to collection variable
2. Get Products → product ID saved for next request
3. Add to Cart → cart ID saved from response
4. Place Order → order ID saved from response
5. Logout → token cleared and verified

## Assertions Covered

- Status code validation (200, 201)
- Field existence checks (token, cart ID, order ID)
- Data type validation (string, number)
- Pre-request variable checks before each call

## Tools Used

- Postman
- JavaScript (pm.test assertions)
- Collection Variables for chaining

## How to Run

1. Import `ecommerce-api-tests.json` into Postman
2. Set `baseUrl` variable to your API base URL
3. Click Run Collection
4. Tests execute in order automatically

## What I Learned

- How to chain API requests using collection variables
- How to auto-save and reuse Bearer tokens
- Writing JavaScript assertions in Postman Tests tab
- Pre-request script validation

## Author

Vishnu Durga
github.com/VishnuDurgaCse
