# postman-api-testing
E-commerce API test collection built with Postman

# E-Commerce API Testing — Postman Collection

## What this project covers
- Complete e-commerce API flow testing
- Login with Bearer token authentication
- Chaining — auto token save and reuse
- Pre-request scripts for dynamic test data
- 15+ assertions per collection run

## Tools Used
- Postman
- Newman CLI
- JavaScript assertions

## API Flow
1. Login → Bearer token auto saved
2. Get Products → verify product list
3. Add to Cart → dynamic cart data
4. Place Order → unique order ID generated
5. Verify Order → assertions on order response

## Assertions covered
- Status code validation
- Response time checks
- Field existence checks
- Data type validation
- Negative testing

## How to run
1. Import collection JSON into Postman
2. Hit Run Collection
3. All 15 tests pass automatically
