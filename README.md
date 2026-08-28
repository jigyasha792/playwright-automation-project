# SauceDemo Login Test Automation

This project contains automated test cases for the login functionality of [SauceDemo](https://www.saucedemo.com/) using Playwright and JavaScript.

## Test Objective

The objective of this project is to automate and verify different login scenarios, including successful and unsuccessful login attempts.

## Technologies Used

* Playwright
* JavaScript
* Node.js
* Git and GitHub

## Test Cases

The following login scenarios have been automated:

| Test Case | Scenario                              | Expected Result                                  |
| --------- | ------------------------------------- | ------------------------------------------------ |
| TC01      | Valid username and valid password     | User should successfully log in                  |
| TC02      | Empty username and password           | Appropriate validation error should be displayed |
| TC03      | Valid username and invalid password   | Appropriate login error should be displayed      |
| TC04      | Invalid username and valid password   | Appropriate login error should be displayed      |
| TC05      | Invalid username and invalid password | Appropriate login error should be displayed      |

## Browsers Tested

The automated tests were executed across multiple browsers:

* Chromium
* Firefox
* WebKit

## Test Results

All five test cases were executed successfully across all three browsers.

| Browser   | Test Cases | Result     |
| --------- | ---------: | ---------- |
| Chromium  |          5 | Passed     |
| Firefox   |          5 | Passed     |
| WebKit    |          5 | Passed     |
| **Total** |     **15** | **Passed** |

The complete test execution took approximately **30.2 seconds**.

## Project Structure

```text
Automation-Project/
├── tests/
│   └── saucedemo.spec.js
├── playwright.config.js
├── package.json
├── package-lock.json
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Navigate to the project directory:

```bash
cd YOUR-REPOSITORY
```

Install the dependencies:

```bash
npm install
```

Install Playwright browsers:

```bash
npx playwright install
```

## Running the Tests

Run all tests:

```bash
npx playwright test
```

Run the SauceDemo test file:

```bash
npx playwright test tests/saucedemo.spec.js
```

Run the tests with the browser visible:

```bash
npx playwright test --headed
```

Run the Playwright UI:

```bash
npx playwright test --ui
```

## Test Report

After executing the tests, view the Playwright HTML report using:

```bash
npx playwright show-report
```

## Author

**Jigyasha Balkoti**
