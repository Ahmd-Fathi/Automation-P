# Website Automation Testing

## Overview
This repository contains an automation testing task using Java and Selenium to simulate the creation of course scenarios on the [Winjigo website](https://swinji.azurewebsites.net).

## Task Details
The objective of this automation task is to simulate the creation of course scenarios by performing a series of actions on the Winjigo website. The scenario includes steps such as signing in, navigating to the courses page, creating a new course, filling in basic course information, and asserting that the course title is displayed.

### Scenario Steps:
1. Open [https://swinji.azurewebsites.net](https://swinji.azurewebsites.net) website.
2. Sign in with the username `testregister@aaa.com` and password `Wakram_123`.
3. Open the courses page from the left side navigation bar.
4. Click on the "Create Course" button.
5. Fill in course basic info, then click "Save".
6. Go back to the courses list page and assert that the course title is displayed.

## Automation Framework Details
This automation task is implemented using Java and Selenium WebDriver.

### Key Concepts:
1. **Locators in Selenium:**
   - Selenium supports various types of locators such as ID, Name, XPath, CSS Selector, Class Name, Link Text, and Partial Link Text.

2. **WebDriver Drivers:**
   - Different types of WebDriver drivers are available, including ChromeDriver, FirefoxDriver, EdgeDriver, etc.

3. **Waits in WebDriver:**
   - Selenium provides Implicit Waits, Explicit Waits, and Fluent Waits to handle synchronization issues.

4. **driver.quit() vs driver.close():**
   - `driver.quit()` closes all browser windows and ends the WebDriver session.
   - `driver.close()` closes the current browser window.

## Getting Started
To run the automation script, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

2. **Install Dependencies:**
    - Make sure you have Java and Selenium WebDriver set up.

3. **Run the Automation Script:**
    ```bash
    # Assuming your script is named 'AutomationScript.java'
    java AutomationScript.java
    ```

## Contributions
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

Feel free to explore the code and adapt it to your specific needs. Happy testing!
