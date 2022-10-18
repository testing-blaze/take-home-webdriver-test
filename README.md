How To Run Tests?
- Go to any test class, left click and select Run.
- Go to testng.xml, left click and select Run to run full suite.
- Go to terminal and project root and use maven command: mvn clean verify -DsuiteXmlFile=testng.xml

Disclaimer: As this activity is only for assignment purpose, so no reporting addon is included.
Default Browser: Chrome
Choose a Browser: mvn clean verify -DsuiteXmlFile=testng.xml -Dbrowser=FIREFOX

Project Structure:

- testcase package: All Test cases
- pageobject package: All relevant page objects
- main-resource: Contains file to be uploaded
- framework-libraries: Contains all core library wrappers consumed in automation of tests.