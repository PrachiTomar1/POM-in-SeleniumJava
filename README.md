# POM-in-SeleniumJava
# Author Name - Prachi Tomar
# What is POM?
1. Page Object Model (POM) is a design pattern used in Selenium automation testing to create object repositories for web elements.
2. A design pattern that improves code reusability, maintainability, and readability by creating separate page classes for UI elements.
3. It helps in maintaining clean, reusable, and easy-to-maintain code.
4. Instead of writing locators and methods directly in test scripts, POM separates UI interactions from test cases by storing them in separate Java classes.

#  Advantages of POM:
1. Code Reusability – Common methods can be reused across multiple tests.
2. Code Maintainability – Changes in UI require updates only in one place.
3. Readability & Clean Code – Reduces code duplication and improves structure.
4. Separation of Concerns – Keeps test scripts and UI logic separate.

# How to Implement POM in Selenium Java?
# #Step 1: Create a Page Class
1. Each web page is represented as a class, and web elements are defined as variables using @FindBy annotation with PageFactory.
# #Step 2: Create a Test Class
1. Use the LoginPage object inside the test class to perform login actions.
# #Step 3: Running the Test
1. The test initializes the driver, navigates to the login page, and performs login operations using POM.
2. If the UI changes, only LoginPage.java needs to be updated, keeping tests unaffected.
   
