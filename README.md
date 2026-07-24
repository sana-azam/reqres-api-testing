# Reqres API Testing Project

## Project Overview

This project demonstrates manual API testing performed on the Reqres REST API using Postman. The objective of this project was to validate API functionality, response behavior, input validation, data handling, and error responses through different positive and negative test scenarios.

The project includes API test cases, Postman collection, test execution results, bug reports, and supporting screenshots.

---

## Project Details

**Project Name:** Reqres API Testing  
**Testing Type:** Manual API Testing  
**Tester:** Sana  
**Reviewed By:** Ahmed  
**Version:** 1.0  

---

## Tools & Technologies Used

- Postman
- REST APIs
- JSON
- Microsoft Excel
- GitHub

---

## API Under Test

**API Platform:** Reqres

Reqres is a hosted REST API service used for testing and prototyping frontend and backend applications.

The following HTTP methods were tested:

- GET Requests
- POST Requests

---

## Testing Scope

The following areas were covered during API testing:

### 1. Request Validation

- Validation of request parameters
- Validation of required fields
- Validation of input data types

### 2. Response Validation

- API response verification
- Response data verification
- HTTP response behavior validation

### 3. Input Validation Testing

- Minimum and maximum value validation
- Field type validation
- Negative test scenarios
- Invalid parameter handling

### 4. Data Processing Testing

- User creation flow
- ID generation validation
- Request and response body verification
- CSV file upload testing

### 5. JSON Validation

- JSON structure validation
- JSON schema verification

---

## Test Coverage

A total of **20 test cases** were executed covering both positive and negative scenarios.

| Category | Coverage |
|---|---|
| GET API Testing | 10 Test Cases |
| POST API Testing | 10 Test Cases |
| Positive Test Cases | Valid input and successful responses |
| Negative Test Cases | Invalid input and error handling |

---

## Test Scenarios Covered

The following scenarios were tested:

- Verify API response
- Validate minimum and maximum input ranges
- Validate JSON schema
- Verify response data accuracy
- Validate field data types
- Verify incorrect parameter handling
- Verify invalid URL handling
- Verify negative parameter behavior
- Verify user creation functionality
- Verify CSV file upload functionality

---

## Defect Summary

During testing, multiple validation and response handling issues were identified.

Examples:

- API accepted numeric values in fields requiring alphabetic characters
- API processed invalid parameters without returning errors
- API returned incorrect responses for invalid requests
- API returned all records instead of requested user-specific data

Detailed defect information is available in the Bug Reports folder.

---

## Project Structure

Reqres-API-Testing
│
├── README.md
│
├── Postman
│ └── Reqres_API_Collection.json
│
├── Test-Cases
│ └── API_Test_Cases.xlsx
│
├── Test-Execution-Results
│ └── Test_Execution_Report.xlsx
│
├── Bug-Reports
│ └── API_Bug_Report.xlsx
│
└── Screenshots
├── Postman_Collection.png
├── API_Request_Response.png
└── Test_Execution_Result.png

---

## Key Learning Outcomes

- Performed manual API testing using Postman
- Created and executed API test cases
- Validated API responses and error handling
- Documented defects and test execution results
- Worked with REST APIs and JSON data validation

---

## Author

**Sana**  
QA Tester | Manual Testing | API Testing
