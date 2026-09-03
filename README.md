# API Testing with Playwright

## Overview

A beginner-friendly API automation project created using **Playwright and JavaScript**. The project demonstrates testing REST APIs using different HTTP methods and validating API responses.

## Tools & Technologies

* Playwright
* JavaScript
* Node.js
* REST API
* Reqres API
* VS Code

## API Tests Covered

* **GET** - Retrieve user details and validate the response
* **POST** - Create a new user and validate the response
* **PUT** - Update user details and validate the response
* **DELETE** - Delete a user and validate the response
* Status code and response content validation
* JSON response logging

## Playwright Features

* API Request Context
* UI Mode for test execution and debugging
* Console logs and error inspection
* HTML Test Reports

## Project Setup

```bash
npm init playwright@latest
```

Run tests:

```bash
npx playwright test
```

Run in UI Mode:

```bash
npx playwright test --ui
```

View HTML Report:

```bash
npx playwright show-report
```

## API Used

[Reqres](https://reqres.in/)

## References

[Playwright API Testing Documentation](https://playwright.dev/docs/api-testing)

[Playwright APIRequestContext](https://playwright.dev/docs/api/class-apirequestcontext)
