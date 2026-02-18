🧪 nopCommerce Admin Login Automation
<p align="center"> <!-- Tech Badges --> <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk" /> <img src="https://img.shields.io/badge/Selenium-Automation-green?style=for-the-badge&logo=selenium" /> <img src="https://img.shields.io/badge/Cucumber-BDD-brightgreen?style=for-the-badge&logo=cucumber" /> <img src="https://img.shields.io/badge/TestNG-Testing-red?style=for-the-badge" /> <img src="https://img.shields.io/badge/Log4j2-Logging-blue?style=for-the-badge" /> <img src="https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge&logo=apachemaven" /> </p>
📌 Project Description

Automation framework developed using BDD (Behavior Driven Development) approach to test login scenarios for:

🔗 Application Under Test:
http://admin-demo.nopcommerce.com/login

The framework validates different login scenarios for the nopCommerce Admin Portal.

🛠️ Tech Stack

☕ Java

🥒 Cucumber (BDD)

🌐 Selenium WebDriver

🧪 TestNG

📦 Maven

📝 Log4j2

📂 Project Structure
nopcommerce-login-automation
│
├── src/test/java
│   ├── stepDefinitions
│   ├── pageObjects
│   ├── runners
│
├── src/test/resources
│   ├── features
│   │   └── login.feature
│   ├── config.properties
│
├── pom.xml
└── README.md

🧪 Test Scenarios Covered
✅ Valid Login Scenario

User enters valid email and password

User clicks login

User is redirected to dashboard

❌ Invalid Login Scenario

User enters invalid credentials

Error message is displayed

⚠️ Empty Fields Validation

User tries to login without entering credentials

Validation messages are displayed

▶️ How to Run the Project
1️⃣ Clone Repository
git clone https://github.com/your-username/your-repo.git

2️⃣ Run with Maven
mvn clean test

3️⃣ Run Specific Runner

Run the TestNG runner class from your IDE.

📊 Reporting

TestNG Reports

Cucumber HTML Reports

Console Logs with Log4j2

Reports are generated under:

/target/cucumber-reports

🧱 Framework Design Pattern

Page Object Model (POM)

BDD with Gherkin

Reusable Step Definitions

Configurable test properties

Logging implementation with Log4j2

👨‍💻 Author

Automation Project for practice and demonstration purposes.
