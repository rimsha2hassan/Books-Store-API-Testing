# Books-Store-API-Testing

This repository contains a Postman collection used for testing various endpoints of the Simple Books API. The collection includes comprehensive test cases covering authentication, data validation, error handling, and ensuring the API behaves as expected.

# Contents
API_Test_Collection.json: The exported Postman collection containing all the requests and tests.
README.md: Documentation and instructions on how to use the Postman collection.

# How to Use the Postman Collection
## 1. **Importing the Collection into Postman**

  - Download the API_Test_Collection.json file from this repository.
  - Open Postman.
  - Click on the Import button in the top left corner of the Postman app.
  - Select the Choose Files option and upload the API_Test_Collection.json file.
  - The collection should now be visible in your Postman app under the Collections tab.

## 2. Running the Tests
 1. Select the collection in Postman.
 2. Click the Run button to execute all the requests in the collection or select individual requests to run specific tests.
Review the test results in the Postman console.

## 3. Environment Setup (Optional)
 If the collection uses environment variables (e.g., for API keys or tokens), ensure you set up the necessary variables in Postman before running the tests.

# Test Cases Covered
## 1. Authentication Validation
 - Unauthorized Access: Validates that the API returns a 401 Unauthorized status when an invalid bearer token is provided.

## 2. Data Validation
 - Required Fields: Ensures that all required fields are provided and meet the necessary constraints.
 - Valid Data Types: Verifies that the data types of inputs match the expected types.

## 3. Error Handling
 - 404 Errors: Verifies that accessing non-existent resources returns a 404 Not Found status.
 - Invalid Data: Ensures proper error messages are returned when invalid data is submitted.

## 4. Schema Validation
 - JSON Schema Validation: Checks that the structure of the JSON response matches the predefined schema.

## 5. Response Time Validation
 - Performance Testing: Validates that the API responds within an acceptable time limit (e.g., less than 200ms).

## 6. Status Code Validation
- Expected Status Codes: Ensures that the correct status code is returned for each API request (e.g., 200, 201, 400, 401, 404).

## 7. Chaining Requests
 - Workflow Automation: Chains requests together by using the output of one request as the input for another.

## 8. Pagination Validation
 - Pagination Testing: Verifies that the API returns the correct number of items per page and handles pagination correctly.

## Additional Information
 - API Documentation: Simple Books API Documentation provides detailed information on the available endpoints.
 - Postman Documentation: For more details on using Postman, refer to the Postman Learning Center.

## Contributing
If you'd like to contribute to this project, feel free to submit a pull request or open an issue with your suggestions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
