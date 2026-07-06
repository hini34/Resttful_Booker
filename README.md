# RESTful Booker API Testing Project

## Project Name

RESTful Booker API Testing


## Objective

In this project, I performed API testing on the RESTful Booker application using Postman. My main objective was to verify that all APIs are working correctly for both positive and negative scenarios. I also validated status codes, response body, response time, headers, authentication, and error handling. After execution, I prepared the Test Plan, Test Scenarios, Test Cases, RTM, Bug Report, and Newman Report.


## APIs Tested

- GET /ping (Health Check)
- POST /auth
- GET /booking
- GET /booking/{id}
- POST /booking
- PUT /booking/{id}
- PATCH /booking/{id}
- DELETE /booking/{id}


## Tools Used

- Postman
- Newman
- Microsoft Excel
- Microsoft Word


## Project Deliverables

- Test Plan
- Test Scenarios
- Test Cases
- Requirement Traceability Matrix (RTM)
- Bug Report
- Postman Collection
- Postman Environment
- Newman HTML Report


## Testing Summary

- Total APIs Tested : 8
- Total Test Scenarios : 23
- Total Test Cases : 106
- Passed Test Cases : 100
- Failed Test Cases : 6
- Bugs Reported : 6


## Bugs Found

During testing, I found the following issues:

- Booking was created even when firstname was blank.
- Booking was created even when lastname was blank.
- Booking was created with an invalid totalprice value.
- API returned Internal Server Error when bookingdates was missing.
- API returned Internal Server Error when the request body was empty.
- PUT API returned 403 Forbidden for an empty request body instead of a validation error.


## Conclusion

I successfully completed the API testing of the RESTful Booker application. I tested all available APIs, created positive and negative test cases, executed them using Postman, and generated the Newman report. I also documented all identified issues in the Bug Report and mapped the requirements with test scenarios and test cases using the RTM.



## Created By
Hini Patel


