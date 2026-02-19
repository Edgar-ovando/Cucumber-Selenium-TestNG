<h1> 🚀  Test Automation Framework </h1>

## 📌 Project Description

The framework validates different login scenarios for the nopCommerce Admin Portal.

🔗 Web Application Link:
```
http://admin-demo.nopcommerce.com/login
```
---

## 🛠️ Tech Stack

<ul>
  <li>
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java Badge"/>
  </li>
  <li>
    <img src="https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white" alt="Cucumber Badge"/>
  </li>
  <li>
    <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium Badge"/>
  </li>
  <li>
    <img src="https://img.shields.io/badge/TestNG-FF6F00?style=for-the-badge&logo=testng&logoColor=white" alt="TestNG Badge"/>
  </li>
  <li>
    <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven Badge"/>
  </li>
  <li>
    <img src="https://img.shields.io/badge/Log4j2-2C2255?style=for-the-badge&logo=apache&logoColor=white" alt="Log4j2 Badge"/>
  </li>
</ul>


---

## 🧪 Test Scenarios Covered

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

## 🧱 Framework Design Pattern

✅ Page Object Model (POM)

✅ BDD with Gherkin

✅ Reusable Step Definitions

✅ Configurable test properties

✅ Logging implementation with Log4j2

---

## 📊 Reporting

- TestNG Reports

- Cucumber HTML Reports

- Console Logs with Log4j2

Reports are generated under:
```
/target/cucumber-reports
```
---

## ▶️ How to Run the Project

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

## 📂 Project Structure
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

👨‍💻 Author

Automation Project for practice and demonstration purposes.

