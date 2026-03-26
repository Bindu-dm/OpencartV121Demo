# 🛒 OpenCart Automation Framework

## 📌 Project Overview

This project is an automation testing framework developed for the OpenCart e-commerce application. It is built using Selenium WebDriver with Java and follows a structured approach for maintainability and scalability.

---

## 🚀 Tech Stack

* Java
* Selenium WebDriver
* TestNG
* Maven
* Apache POI (for Excel handling)
* Log4j (for logging)
* Extent Reports (for reporting)

---

## 📂 Project Structure

```
OpencartV121
│── src/test/java
│   ├── testCases          # Test scripts
│   ├── pageObjects        # Page Object Model classes
│   ├── utilities          # Utility classes (Excel, config, etc.)
│   ├── testBase           # Base class (driver setup, common methods)
│
│── src/test/resources
│   ├── config.properties  # Configuration file
│   ├── log4j2.xml         # Logging configuration
│
│── testng.xml             # TestNG suite file
│── pom.xml                # Maven dependencies
│── README.md              # Project documentation
```

---

## ⚙️ Features

* Page Object Model (POM) design pattern
* Data-driven testing using Excel
* Logging using Log4j
* Reporting using Extent Reports
* Cross-browser support (if implemented)
* Reusable utility methods

---

## ▶️ How to Run the Project

### 🔹 Using Eclipse

1. Import project as Maven project
2. Right-click on `testng.xml`
3. Select **Run As → TestNG Suite**

---

### 🔹 Using Maven (Command Line)

```
mvn test
```

---

## 📊 Reports

* Test execution reports are generated using Extent Reports
* Logs are captured using Log4j

---

## 🧠 Key Learnings

* Selenium automation framework design
* TestNG annotations and execution flow
* Maven dependency management
* Data-driven testing using Apache POI
* Git & GitHub for version control

---

## 🔗 GitHub Repository

👉 https://github.com/Bindu-dm/OpencartV121.git

---

## 👩‍💻 Author

**Bindu DM**

---
