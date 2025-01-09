Overview
This project demonstrates a set of Postman API tests for validating EasyPost API endpoints. The collection includes:

Address Verification:

Verifies the accuracy of address details.
Ensures proper error handling and response validation.
Shipment Details Retrieval:

Fetches shipment details using a predefined shipment ID.
Validates response properties like retail_rate and list_rate.
Design Decisions
Validation Tests:

Focused on ensuring API responses meet functional and business logic requirements.
Used Postman’s built-in testing capabilities with JavaScript for response validation.
Modular Requests:

Organized requests for reusability and readability.
Authentication:

Utilized Basic Auth with a secure API key.
Steps to Execute
Setup Postman:

Import the Impledge_QA_AnujShakya.postman_collection.json file into Postman.
Set Environment Variables (if needed):

Define any required variables such as API_KEY or endpoint parameters.
Run the Collection:

Use the Collection Runner to execute all tests sequentially.
Observe test results in the Postman Test Results section.
