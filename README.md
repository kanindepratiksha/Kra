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
```
node -v
npm -v
```


### ⚙️ Setup Instructions
## Clone or unzip the project:
```
git clone <repository-url>
```
OR download and unzip the project folder.

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
healthconnect-e2e/
│
├── .github/                         # GitHub workflows / configs (if any)
│
├── node_modules/                    # Installed dependencies
│
├── playwright-report/               # Playwright HTML reports
│   ├── data/
│   └── index.html
│
├── src/
│   ├── fixtures/                    # Test data and fixtures
│   │   └── testData.ts
│   │
│   ├── pages/                       # Page Object Model (POM)
│   │   ├── BasePage.ts
│   │   ├── LoginPage.ts
│   │   ├── RegistrationPage.ts
│   │   ├── SearchPage.ts
│   │   ├── AppointmentBookingPage.ts
│   │   ├── DoctorDashboardPage.ts
│   │   ├── DoctorProfileSetupPage.ts
│   │   ├── PatientDashboardPage.ts
│   │   └── PaymentPage.ts
│   │
│   └── utils/                       # Utility & helper functions
│       ├── apiHelper.ts
│       ├── auth.ts
│       └── env.ts
│
├── test-results/                    # Execution artifacts
│   ├── error-context.md
│   ├── test-failed-1.png
│   └── video.webm
│
├── tests/
│   ├── sanity/                      # Sanity test suite
│   │   ├── 00_registration.spec.ts
│   │   ├── 01_login.spec.ts
│   │   ├── 02_doctor_profile_setup.spec.ts
│   │   ├── 03_patient_search_and_book.spec.ts
│   │   ├── 04_doctor_sees_appointment.spec.ts
│   │   └── 05_patient_payment_and_review.spec.ts
│   │
│   └── regression/                  # Regression test suite
│       └── 06_medical_records_access.spec.ts
│
├── .env                             # Environment variables
├── .env.example                     # Sample env configuration
│
├── playwright.config.ts             # Playwright configuration
├── package.json                     # Project dependencies & scripts
├── package-lock.json
├── tsconfig.json                    # TypeScript configuration
└── README.md                        # Project documentation

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


