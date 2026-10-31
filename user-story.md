# Customer Accounts Microservice – User Stories

## User Story 1: Create an Account
As a customer, I want to create an account so that my information can be stored.

Acceptance Criteria:
- The customer can submit their name, email, and address.
- Phone number is optional.
- The service assigns a unique account ID.
- Successful creation returns HTTP 201.

## User Story 2: Read an Account
As a user, I want to retrieve an account by ID so that I can view customer details.

Acceptance Criteria:
- The API accepts an account ID.
- The service returns the matching account.
- A missing account returns HTTP 404.

## User Story 3: Update an Account
As a user, I want to update an existing account so that customer information remains accurate.

Acceptance Criteria:
- The API accepts updated account information.
- The service updates the matching account.
- A missing account returns HTTP 404.

## User Story 4: Delete an Account
As a user, I want to delete an account so that outdated records can be removed.

Acceptance Criteria:
- The API accepts an account ID.
- The service deletes the matching account.
- Successful deletion returns HTTP 204.

## User Story 5: List All Accounts
As a user, I want to retrieve all accounts so that I can view stored customer records.

Acceptance Criteria:
- The API returns all accounts.
- The response is in JSON format.
- Successful retrieval returns HTTP 200.
