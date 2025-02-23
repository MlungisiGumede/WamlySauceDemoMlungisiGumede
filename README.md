This repository contains an automated end-to-end test suite for SauceDemo using Selenium,Java and TestNG.

Prerequisites


Ensure you have the following installed on your system:

-Java
-Eclipse IDE
-Maven 
-Google Chrome /firefox
-WebDriverManager (handled via dependencies)


Install Dependencies

-Ensure all required dependencies are installed via Maven

Running the Tests Locally
-Using TestNG in Eclipse

-Open Eclipse.

-Navigate to src/test/Java/Test

-Right-click the testcase file.

-Select Run As > TestNG Suite.


Test Report Generation

After execution, test reports are generated in the C:\Users\gummlu01\eclipse-workspace\saucedemo\test-output\old directory.

To open the report:

-Navigate to C:\Users\gummlu01\eclipse-workspace\saucedemo\test-output\old.

-Open the generated index.html  in your browser.


Assumptions

-The tests assume the application is accessible at https://www.saucedemo.com/.

-Default login credentials provided by SauceDemo are used.

-WebDriverManager is used to handle browser drivers automatically.

-It is assumed that an extension for extensive E2E test can be implemented in the framework


Executable Test cases for POC
-CartTest.java
-LockedUserTest.java
-LoginTest.java
-ProductSortTest.java

MlungisI Gumede:(+27)065 304 6956
u19074362@tuks.co.za


