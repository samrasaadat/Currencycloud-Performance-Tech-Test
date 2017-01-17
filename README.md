# Currencycloud-Performance-Tech-Test


## Scenario:

A new Payments API has been delivered. This API allows users to create new payment records, amend details after submission, search for existing payments, and delete payment records as required. The API returns JSON responses and performs error handling in the event of an invalid request taking place.

## Acceptance Criteria:

You are required to develop a user journey in a tool of your choice which will:
- Perform User Login and retrieve a login token
- Create a new payment record
- Update the reference in the new payment record with a randomly generated string
- Search for a payment record and assert the reference matches the generated string
- End the API Session

## Deliverable:

A bundled repository including a README file with explanation of technology choices and any instructions required to run / assess your solution. Example using Git:

``git bundle create <yourname>.bundle --all --branches``


## Additional Information:

We do not have a public facing test environment for you to write your script against, so it isn't necessary for this test to be perfectly executable.

Extra credit will be given for the demonstration and proper use of:
- Adding loops and conditionals (extend test with error case scenario, conditional statement to retry request with new POST data)
- Incorporating endpoint mocking as a background step so that the script can be run

## Helpful Links:

**CurrencyCloud API Documentation:** https://developer.currencycloud.com/documentation/api-docs/overview/



