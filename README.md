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

Verify installation:
```bash
node -v
npm -v
⚙️ Setup Instructions
Clone or unzip the project:

bash
Copy code
git clone <repository-url>
OR unzip the provided automation package.

Navigate to the project directory:

bash
Copy code
cd healthconnect-automation
Install dependencies:

bash
Copy code
npm install
Install Playwright browsers:

bash
Copy code
npx playwright install
▶️ How to Run Tests
Run all tests
bash
Copy code
npx playwright test
Run specific test using tag
bash
Copy code
npx playwright test -g "ST_05"
Run tests in headed mode
bash
Copy code
npx playwright test --headed
Run tests in a specific browser
bash
Copy code
npx playwright test --project=chromium
📊 Test Report
After execution, Playwright generates an HTML report.

📁 Report Location
text
Copy code
playwright-report/index.html
Open the report
bash
Copy code
npx playwright show-report
📂 Project Structure
text
Copy code
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
✅ Key Highlights
Sanity automation for core workflows

Tag-based execution support

HTML reporting

Scalable Playwright framework

AI-assisted test design approach

🧠 Notes
Test credentials are handled via test data or environment variables.

Ensure the HealthConnect application is accessible before execution.

Tests are designed to be independent and reusable.

👩‍💻 Author
Pratiksha Kaninde
QA Automation Engineer

yaml
Copy code

---

If you want, I can also:
- 🔹 Add **AI tools usage (ChatGPT/Copilot/Cursor)** section  
- 🔹 Make it **100% rubric-aligned**
- 🔹 Convert it into **PDF or DOC**

Just tell me 👍







You said:
i am using github and i will do copy paste give me evrything as ready



ChatGPT said:
Perfect 👍
This is 100% GitHub-ready. You can copy → paste → commit with zero edits.

✅ Steps (do this once)
Open your GitHub repo

Click Add file → Create new file

File name: README.md

Paste everything below

Click Commit new file

📄 READY-TO-PASTE README.md
md
Copy code
# 🧪 HealthConnect – QA Automation Framework

## 📌 Project Overview
This repository contains automated **sanity test suites** for **HealthConnect**, a telemedicine platform used for appointment booking and patient record management.

The framework is built using **Playwright** and focuses on validating critical end-to-end user workflows such as authentication, appointments access, and patient records authorization.

---

## 🛠️ Prerequisites
Make sure the following are installed on your system:

- **Node.js** (v18 or higher)
- **npm** (bundled with Node.js)
- **Visual Studio Code** (recommended IDE)
- **Git** (for version control)

Verify installations:
```bash
node -v
npm -v
⚙️ Setup Instructions
Clone the repository

bash
Copy code
git clone <repository-url>
OR download and unzip the project folder.

Navigate to the project directory

bash
Copy code
cd healthconnect-automation
Install project dependencies

bash
Copy code
npm install
Install Playwright browsers

bash
Copy code
npx playwright install
▶️ Test Execution
Run all tests
bash
Copy code
npx playwright test
Run a specific test by tag
bash
Copy code
npx playwright test -g "ST_05"
Run tests in headed mode
bash
Copy code
npx playwright test --headed
Run tests in a specific browser
bash
Copy code
npx playwright test --project=chromium
📊 Test Reports
Playwright generates an HTML execution report after every run.

📁 Report Location
text
Copy code
playwright-report/index.html
📌 View Report
bash
Copy code
npx playwright show-report
📂 Project Structure
text
Copy code
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
✅ Framework Highlights
End-to-end sanity automation

Role-based access validation

Tag-based test execution

Playwright HTML reporting

Clean and scalable framework design

AI-assisted test case creation

🧠 Notes
Test credentials are managed using test data files or environment variables.

Application under test must be accessible before execution.

Tests are independent and can be executed in isolation.

👩‍💻 Author
Pratiksha Kaninde
QA Automation Engineer

yaml
Copy code
