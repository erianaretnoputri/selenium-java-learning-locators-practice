Selenium Locators Practice
This repository contains an automation script developed using Selenium WebDriver and Java. The project focuses on mastering various Locator Strategies to interact with web elements effectively.

🛠️ Tech Stack
- Language: Java
- Automation Tool: Selenium WebDriver
- Build Tool: Maven (Recommended)
- Browser: Google Chrome (ChromeDriver)

📋 Features & Locators Covered
- The script (Locators.java) demonstrates how to handle various UI components on the Rahul Shetty Academy Practice Page:
- Login Process: Utilizing id, name, and className.
- Error Handling: Capturing and validating dynamic error messages using cssSelector.
- Password Reset: Navigating through reset forms using linkText and complex xpath (indexing).
- Advanced Selectors: * Using nth-child in CSS Selectors.
- Using contains() and attribute-based matching in XPath.

Handling Implicit Waits to manage synchronization issues.

🚀 How to Run
- Clone the repository:

Bash
```
git clone [https://github.com/your-username/selenium-java-locators-practice.git](https://github.com/your-username/selenium-java-locators-practice.git)
git clone https://github.com/your-username/selenium-java-locators-practice.git
git clone [https://github.com/your-username/selenium-java-locators-practice.git](https://github.com/your-username/selenium-java-locators-practice.git)
```
Setup Driver:
Ensure you have ChromeDriver installed. Update the path in the script to match your local directory:

Java
```System.setProperty("webdriver.chrome.driver", "D:/Your/Path/To/chromedriver.exe");```
Execution:
Run the Locators.java file as a Java Application in your IDE (Eclipse, IntelliJ, or VS Code).
