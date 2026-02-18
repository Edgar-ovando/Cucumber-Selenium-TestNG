<h1> 🧪 Test Automation Framework using Java + Cucumber BDD + Selenium + TestNG </h1>

## 📌 Project Description

Automation framework developed using BDD (Behavior Driven Development) approach to test login scenarios for:

🔗 Web Application Link:
```
http://admin-demo.nopcommerce.com/login
```

The framework validates different login scenarios for the nopCommerce Admin Portal.

---

🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium">
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman">  
</p>

---

📂 Project Structure
```
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
```
---
🧪 Test Scenarios Covered

✅ Valid Login Scenario

- User enters valid email and password

- User clicks login

- User is redirected to dashboard

❌ Invalid Login Scenario

- User enters invalid credentials

- Error message is displayed

⚠️ Empty Fields Validation

- User tries to login without entering credentials

- Validation messages are displayed

---

▶️ How to Run the Project
1️⃣ Clone Repository
```
git clone https://github.com/your-username/your-repo.git
```
2️⃣ Run with Maven
```
mvn clean test
```

3️⃣ Run Specific Runner
```
Run the TestNG runner class from your IDE.
```
---

📊 Reporting

- TestNG Reports

- Cucumber HTML Reports

- Console Logs with Log4j2

Reports are generated under:
```
/target/cucumber-reports
```

---

🧱 Framework Design Pattern

Page Object Model (POM)

BDD with Gherkin

Reusable Step Definitions

Configurable test properties

Logging implementation with Log4j2

---

👨‍💻 Author

Automation Project for practice and demonstration purposes.
