
GoRest API Test

This submission contains a Postman collection and environment for testing the(https://gorest.co.in) public API.

Files Included

GoRest-API-Test.postman_collection.json: Postman collection with test scenarios
GoRest-Environment.postman_environment.json: Postman environment file with base URL and token variable

Steps to Execute the Tests

1. Install Postman (if not already installed) from (https://www.postman.com/downloads/)

2. Import Files
   - Open Postman
   - Click Import
   - Choose and import both JSON files:
     - GoRest-API-Test.postman_collection.json
     - GoRest-Environment.postman_environment.json

3. Set the Environment
   - In the top right, select the imported environment: GoRest Environment

4. Update Token
   - Go to the environment settings.
   - Replace 'your_token_here' with your personal access token from (https://gorest.co.in - https://gorest.co.in/my-account/access-tokens)

5. Run the Requests
   - Open the collection 'GoRest API Test'
   - Send the two requests:
     1. Create New User - Verify ID Format
     2. Verify First User Status

Each request includes test scripts that validate the expected outcomes.

-----------------------------------------------------------------------------------------------------------

Scenarios Covered

1. Create a new user using 'POST /users', and verify the returned ID is a number.
2. Get users using 'GET /users', and verify the first user's status is either 'active' or 'inactive'.

