# 🧪 HealthConnect – QA Automation Framework

## 📌 Project Overview
This project contains automated sanity test suites for **HealthConnect**, a telemedicine platform used for appointment booking and patient record management.

The automation framework is built using **Playwright** and focuses on validating critical user workflows such as:
- User Login
- Appointments access
- Patient records access
- Authorization and access control

---

## 🛠️ Prerequisites
Ensure the following are installed on your system before setup:

- Node.js (v18 or higher)
- npm (comes with Node.js)
- Visual Studio Code (recommended)
- Git (optional)

### Verify installation:
node -v
npm -v


### ⚙️ Setup Instructions
## Clone or unzip the project:
```
git clone <repository-url>
```
OR unzip the provided automation package.

## Navigate to the project directory:
```
cd healthconnect-automation
```
## Install dependencies:
```
npm install
```
## Install Playwright browsers:
```
npx playwright install
```
 ### ▶️ How to Run Tests
 ## Run all tests
```
npx playwright test
```
## Run specific test using tag
```
npx playwright test -g "ST_05"
```
## Run tests in headed mode
```
npx playwright test --headed
```
## Run tests in a specific browser
```
npx playwright test --project=chromium
```
### 📊 Test Report
After execution, Playwright generates an HTML report.

## 📁 Report Location
```
playwright-report/index.html
```
## Open the report
```
npx playwright show-report
```
## 📂 Project Structure
```
healthconnect-automation/
│
├── tests/
│   ├── sanity/
│   │   ├── login.spec.ts
│   │   ├── appointments_records_access.spec.ts
│
├── playwright-report/
│
├── playwright.config.ts
├── package.json
└── README.md
```
### ✅ Key Highlights
- Sanity automation for core workflows
- Tag-based execution support
- HTML reporting
- Scalable Playwright framework
- AI-assisted test design approach

### 🧠 Notes
- Test credentials are handled via test data or environment variables.
- Ensure the HealthConnect application is accessible before execution.

Tests are designed to be independent and reusable.

### 👩‍💻 Author
Pratiksha Kaninde


