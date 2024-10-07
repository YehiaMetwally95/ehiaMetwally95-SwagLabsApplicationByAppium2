- Using SwagLabs Android App as the Application Under Test
- Very Simple script based on Selenium 4 by Java, without using loops, conditions or any complex logics
- Using Fluent Object Model Design Pattern in writing test script and page actions, thus chaining the scenario steps and validations in one line of code
- Using the HomePage as Parent of all pages that inherit locators and actions of Header & Footer from Homepage also for defining common variables that are used across all pages, Thus achieving the right purpose of Inheritance
- Using Base Test Class for defining Before Methods and After Methods, such that all TestCases classes inherit from Base Test class
- Start each test from a clean state by setting and tearing down brower for every Test Case
- Using TestNG as the Testing Framework
- Synchronizing the elements identification and actions on them inside Fluent Wait lambda expression, thus waiting till action is taken not just finding the element
- Implement Util for W3C Touch Actions based on (x y coordinates) to simulate scroll element and scroll screen into view in any direction in addition to other gestures like zooming, drag/drop on Android Apps and IOS Apps
- Implement Util for Touch Actions based on (UI Scrollable and UI Selectors) to simulate scroll element and scroll screen into view in any direction in addition to other gestures like zooming, drag/drop on Android Apps only
- Implement Util for interacting with different Alerts
- Test Data Preparation Statically by setting Json File for every Test which read its data from mysql database using JDBC & Use this data for different validations
- Test Data Generation Dynamically using Time Stamp
- Test Data Execution by reading test data from Json files whether Json data is represend as simple json object or nested objects and array of objects
- Listening to different interactions of driver using TestNG Listeners
- Using Hard assertions after every test & Soft assertions for doing verifications within the test
- Finding Elements using simple Techniques with IDs, Android UI Automator & Advanced Techniques like XPath Axis for nested elements
- Reading Global Variables and Configurations from Properties file & Reading Device and Application Capabilities from a Util for Driver Manager
- Using Allure Report for Reporting Test Result & Taking Screenshots for Successful Tests and Failed Tests and also Failed soft assertions & Logging Test Steps & Defining Epics/Features/Stories
