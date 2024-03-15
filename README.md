# Api Demo App Automation Project

This project contains automated tests for the Api Demo App. It utilizes Appium WebDriver with Java to automate interactions with the app.


## Prerequisites

Before running the tests, ensure you have the following installed:
- Java Development Kit (JDK) 8 or higher
- Appium
- Android Studio
  
You can install the JDK from [here](https://www.oracle.com/java/technologies/javase-downloads.html).

For Maven, add the following dependency to your `pom.xml`:
```xml
      <dependency>
            <groupId>io.appium</groupId>
            <artifactId>java-client</artifactId>
            <version>9.0.0</version>
        </dependency>

        <!-- https://mvnrepository.com/artifact/org.testng/testng -->
        <dependency>
            <groupId>org.testng</groupId>
            <artifactId>testng</artifactId>
            <version>7.8.0</version>
            <scope>test</scope>
        </dependency>

#Project Structure
swag-labs-automation/

│
├── src/
│   ├── main/                              # (if applicable, for application code)
│   │
│   └── test/
│       ├── java/
│          ├── Base/
│          │   ├── TestBase.java         # Base class for test cases
│          │   └── BasePage.java         # Base page class with common functionality
│          │
│          ├── Page/
│          │    └── api_demo     # Page object for login page
│          │    │       └──  ListViewPage.java
                └── BasePage.java
│          ├── TestCase/
│          └── TestCase1.java       # Test case for scenario 1
└── README.md                            # This file








