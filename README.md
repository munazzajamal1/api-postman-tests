# Automate GoREST API Test using Postman

This repository contains Postman API tests for GoREST API(https://gorest.co.in). It demonstrates API testing scenarios including:

- Creating a new user
- Validating user's first entry is only either "active" or "inactive"

---

## Setup

1. Install Postman
2. Download or clone this repository:
   git clone https://github.com/munazzajamal1/api-postman-tests.git

3. Open Postman and import:
   - API Test.postman_collection.json (the test collection)
   - New Environment.postman_environment.json (the environment setup)

4. Set your GoREST API access token (Optional but Recommended)
   The environment file already includes a demo access token. But you can use your own from https://gorest.co.in. Open the imported environment, locate the token variable, and paste your token there (e.g., Bearer <your_token>).

---

## How to Run the Tests

1. In Postman, go to Collection Runner

2. Select the API Test collection

3. Choose New Environment from the environment dropdown

4. Click Run to execute all test scenarios

