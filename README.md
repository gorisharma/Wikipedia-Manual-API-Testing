# Wikipedia – Manual & API Testing Project

## Project Overview

This is a self-initiated QA testing project performed on Wikipedia to practice and demonstrate Manual Testing and API Testing skills.

The project covers functional, UI, usability, positive, negative and API testing of Wikipedia's search, article navigation, language functionality and MediaWiki Search API.

## Application Under Test

- Application: Wikipedia
- Website: https://www.wikipedia.org/
- API: MediaWiki Search API
- API Endpoint: https://en.wikipedia.org/w/api.php
- Testing Type: Manual Testing & API Testing
- API Tool: Postman
- Browser: Brave

## Modules Covered

### Manual Testing
- Home Page
- Search
- Search Results
- Article Page
- Article Navigation
- Internal Links
- Language
- Usability

### API Testing
- Valid Search Requests
- Negative Search Requests
- HTTP Status Code Validation
- JSON Response Validation
- Response Structure Validation
- Search Result Field Validation

## Testing Activities

- Test Planning
- Test Scenario Preparation
- Test Case Design
- Manual Test Execution
- API Test Execution
- Positive Testing
- Negative Testing
- UI Testing
- Usability Testing
- Response Validation
- Defect Identification
- Test Execution Reporting
- Requirement Traceability

## Test Execution Summary

| Testing Type | Total | Passed | Failed | Not Executed |
|---|---:|---:|---:|---:|
| Manual Testing | 50 | 49 | 0 | 1 |
| API Testing | 25 | 25 | 0 | 0 |
| **Overall** | **75** | **74** | **0** | **1** |

### Not Executed Test Case

**TC_014:** Search result navigation across multiple pages could not be verified because the search results were displayed on a single page.

## API Testing

API testing was performed using Postman.

The following areas were validated:

- Valid search requests
- Invalid/non-existing search requests
- Empty search keyword
- Special characters
- HTTP 200 response
- JSON response format
- Response object structure
- Search array
- Search result fields
- Title field
- Page ID field
- Snippet field

## Defect Summary

No reproducible defect was identified during the executed test cases.

## Project Structure

```text
Wikipedia-Manual-API-Testing
│
├── 01-Test-Plan
│   └── Wikipedia_Test_Plan.docx
│
├── 02-Test-Scenarios
│   └── Wikipedia_Test_Scenarios.xlsx
│
├── 03-Test-Cases
│   └── Wikipedia_Test_Cases.xlsx
│
├── 04-API-Test-Cases
│   └── Wikipedia_API_Test_Cases.xlsx
│
├── 05-Bug-Reports
│   └── Wikipedia_Bug_Report.xlsx
│
├── 06-RTM
│   └── Wikipedia_RTM.xlsx
│
├── 07-Test-Execution
│   └── Wikipedia_Test_Execution_Report.xlsx
│
├── 08-Postman-Collection
│   └── Wikipedia_API_Testing.json
│
└── Screenshots
    ├── Manual-Testing
    └── API-Testing

## Skills Demonstrated

- Manual Testing
- Test Scenario Design
- Test Case Design
- Functional Testing
- UI Testing
- Usability Testing
- Positive & Negative Testing
- API Testing
- Postman
- HTTP Status Code Validation
- JSON Response Validation
- Defect Reporting
- RTM
- Test Execution Reporting
- Git & GitHub

## Disclaimer

This is a self-initiated QA testing project created for learning and portfolio purposes. It does not represent professional testing experience with Wikipedia.