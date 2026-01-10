# 🏦 Parabank Automation Suite (TDD Framework) 🚀

This repository contains a **Test Automation Framework** developed for **Parabank**, a sample online banking application by **Parasoft**.  
The framework is built using **Java, Selenium WebDriver, TestNG, and Maven**, and follows the **Test-Driven Development (TDD)** approach with a clean **Page Object Model (POM)** architecture.

It demonstrates **real-world automation best practices** including data-driven testing, reporting, logging, and failure handling.

---

## 📌 Project Highlights

- 🔹 Automated end-to-end testing of a **banking web application**
- 🔹 **Test-Driven Development (TDD)** based implementation
- 🔹 Clean and scalable **Page Object Model (POM)**
- 🔹 **Excel-driven test data** using Apache POI
- 🔹 **Extent Reports** with detailed execution insights
- 🔹 **Automatic screenshots** captured on test failures
- 🔹 Centralized **log4j2 logging**
- 🔹 Maven-based project for easy build & execution

---

## ✨ Key Features

✔ User Registration & Login Automation  
✔ Account Overview & Balance Validation  
✔ Fund Transfer Test Scenarios  
✔ Bill Payment & Transaction History Tests  
✔ Data-Driven Testing using Excel  
✔ Cross-browser ready architecture  
✔ Failure handling with screenshots  
✔ Detailed HTML execution reports  

---

## 📁 Project Structure
```
Parabank_V1.2/
│
├── src/main/java
│   └── (Application source – currently not used)
│
├── src/main/resources
│   └── (Config files if any)
│
├── src/test/java
│   │
│   ├── com.parabank.pages
│   │   ├── HomePage.java
│   │   ├── LoginAccountPage.java
│   │   ├── MyAccountPage.java
│   │   ├── OpenNewAccountPage.java
│   │   └── RegisterPage.java
│   │
│   ├── com.parabank.tests
│   │   ├── BaseClass.java
│   │   ├── TC001_VerifyLogoTest.java
│   │   ├── TC002_RegistrationOfNewUserTest.java
│   │   ├── TC003_UserLoginWithValidCredentialsTest.java
│   │   ├── TC004_VerifyLoginFailureWithEmptyUsernameTest.java
│   │   ├── TC005_VerifyLoginFailureWithIncorrectPasswordTest.java
│   │   ├── TC006_VerifyAccountBalanceDisplayAfterLoginTest.java
│   │   ├── TC007_VerifySuccessfulLogoutTest.java
│   │   ├── TC008_VerifyLoginWithBlankFieldsTest.java
│   │   ├── TC009_VerifyCaseSensitivityInLoginTest.java
│   │   └── TC021_VerifyOpenNewAccountFunctionalityTest.java
│   │
│   └── com.parabank.utils
│       └── ExtentReportManager.java
│
├── src/test/resources
│   └── config.properties
|   └── log4j2.xml
|   └── logo.png
│
├── logs
│   └── execution.log
│
├── reports
│   └── ExtentReport.html
│
├── screenshots
│   └── (Failure screenshots)
│
├── Parabank-official
│   └── (Application reference files)
│
├── target
│   └── (Maven generated files)
│
├── test-output
│   └── (TestNG reports)
│
├── Master.xml
├── ParallelTesting.xml
├── pom.xml
├── README.md
└── run.bat


```
<img width="606" height="744" alt="image" src="https://github.com/user-attachments/assets/78e5623c-cf54-42a0-bd32-15366301bea5" />

---

## 🛠 Tech Stack

| Category | Technology |
|-------|-----------|
| Language | Java |
| Automation Tool | Selenium WebDriver |
| Test Framework | TestNG |
| Build Tool | Maven |
| Design Pattern | Page Object Model (POM) |
| Reporting | ExtentReports |
| Logging | log4j2 |
| Data Handling | Apache POI (Excel) |
| Utilities | Commons IO / Commons Lang |

---

## 🔹 How to Run

- 🔹Clone the repository

- 🔹git clone This repository


- 🔹Open the project in IntelliJ IDEA / Eclipse.

- 🔹Run the following Maven command to clean and execute tests:

- 🔹mvn clean test

- 🔹After execution:

- 🔹Reports will be available under the Reports/ folder

- 🔹Logs will be stored in the logs/ folder

- 🔹Screenshots for failures will be inside Screenshots/

- 🔹 Reports & Logs<br>
- 🔹📊 ExtentReports → Rich HTML reports with detailed steps & screenshots

- 🔹📝 Execution Logs → Captured using Log4j under the logs/ directory

- 🔹📷 Failure Screenshots → Auto-captured for failed test cases
---

## 👨‍💻 Author <br>

Sagar Bankar<br>
Software Test Engineer

🔗 GitHub Profile:
https://github.com/Sagar-bankar <br>
🔗 Visit github page for real Result -->>> [click live Page Result](https://sagar-bankar.github.io/hybrid-framework-portfolio/)<br>
🔗 GitHub Profile: [Parabank Repository TDD Framework](https://github1s.com/sagar-bankar/ParaBank_Automation_Hybrid-Automation-Framework.git)<br>
⭐ If you find this project helpful, please consider giving it a star!
```
---------------------------------------------------------------------------------------------------------------------------------
© 2025 Sagar Bankar. All rights reserved.

This project is shared for educational and portfolio purposes.
Reproduction, commercial use, or redistribution without explicit
permission from the author is not allowed.
---------------------------------------------------------------------------------------------------------------------------------
```
