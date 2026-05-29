# OrangeHRM Playwright Automation Framework

## Overview

This project is an automation testing framework developed using Playwright and JavaScript for the OrangeHRM application.

The framework covers:

* Login Validation
* Invalid Login Validation
* Admin User Search Validation
* API / Network Validation
* Dynamic Table Validation
* Page Object Model (POM)
* HTML Reporting
* Screenshot on Failure

---

## Project Structure

```text
HRM
│
├── tests
│   ├── login.spec.js
│   ├── invalidLogin.spec.js
│   └── adminSearch.spec.js
│
├── pages
│   ├── LoginPage.js
│   └── AdminPage.js
│
├── utils
│   ├── constants.js
│   ├── testData.js
│   └── helper.js
│
├── screenshots
│
├── reports
│
├── playwright.config.js
├── package.json
└── README.md
```

---

## Technologies Used

* Playwright
* JavaScript
* Node.js

---

## Test Scenarios

### 1. Login Validation

* Launch application
* Login with valid credentials
* Validate Dashboard page
* Capture Screenshot
* Validate Login API Response

### 2. Invalid Login Validation

* Login with invalid credentials
* Validate error message
* Validate user remains on login page

### 3. Admin Search Validation

* Navigate to Admin Module
* Search user "Admin"
* Validate dynamic table data
* Validate search results

### 4. API Validation

* Capture login API request
* Validate request method
* Validate response status

---

## Framework Features

* Page Object Model (POM)
* Reusable Methods
* Centralized Test Data
* Centralized Configuration
* HTML Reporting
* Screenshot on Failure
* Video Recording on Failure
* Trace Collection on Failure

---

## Installation

Install dependencies:

```bash
npm install
```

Install Playwright browsers:

```bash
npx playwright install
```

---

## Execute Tests

Run all tests:

```bash
npx playwright test
```

Run a specific test:

```bash
npx playwright test tests/login.spec.js
```

---

## HTML Report

Generate and open the report:

```bash
npx playwright show-report
```

or

```bash
npx playwright show-report reports/html-report
```

---

## Author

Riya Samanta
