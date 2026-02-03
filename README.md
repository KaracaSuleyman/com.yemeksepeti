# Yemeksepeti Mobile Test Automation Framework 🍔📱

[![Java](https://img.shields.io/badge/Language-Java-orange.svg)](https://www.oracle.com/java/)
[![Appium](https://img.shields.io/badge/Mobile-Appium-red.svg)](http://appium.io/)
[![Cucumber](https://img.shields.io/badge/Framework-Cucumber-green.svg)](https://cucumber.io/)
[![Maven](https://img.shields.io/badge/Build-Maven-blue.svg)](https://maven.apache.org/)
[![TestNG](https://img.shields.io/badge/TestRunner-TestNG-brightgreen.svg)](https://testng.org/)

This repository contains a high-level **Mobile Automation Framework** designed for the **Yemeksepeti** Android application. It utilizes the **Behavior-Driven Development (BDD)** approach to ensure clear communication between technical and non-technical stakeholders.

## 🌟 Key Features

- **BDD with Cucumber:** Test scenarios are written in Gherkin language for better readability and collaboration.
- **Page Object Model (POM):** A clean design pattern that enhances code reusability and minimizes maintenance efforts.
- **Robust Locators:** Implementation of dynamic and stable locators to handle the complex UI of a high-traffic delivery app.
- **Custom Utilities:** Specialized helper methods for explicit waits, scrolling, and element interactions.
- **Detailed Reporting:** Integrated with **Allure Report** to provide visual execution summaries and failure analysis.

## 🛠 Tech Stack

* **Language:** Java
* **Mobile Engine:** Appium
* **BDD Framework:** Cucumber (Gherkin)
* **Test Runner:** TestNG / JUnit
* **Dependency Management:** Maven
* **Design Pattern:** Page Object Model (POM)

## 📁 Project Structure

```text
com.yemeksepeti
 ├── src/test/java
 │    ├── step_definitions  # Glue code for Gherkin steps
 │    ├── runners           # Cucumber TestRunner configurations
 │    ├── pages             # Mobile element locators and page-specific actions
 │    └── utils             # Driver Manager, Configuration Reader, and UI Helpers
 ├── src/test/resources
 │    ├── features          # .feature files (User stories and scenarios)
 │    └── configuration.properties # Environment and device settings
 └── pom.xml                # Project dependencies and plugins
