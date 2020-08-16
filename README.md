# BDD_Cucumber_Hybrid

This project is designed by using hybrid framework technique. It uses Page Object Model architecture along with BDD Cucumber.

In this project script is written in java language using tool Selenium Webdriver.

This project scripted using build management tool Maven and integrated with TestNG framework.

Project can be executed using both Junit(using testngCucumber.xml file Execute TestRunner class of cucumber) and Testng framework(using testng.xml file).

Project can also run through Maven by modifying xmls(testngCucumber.xml or testng.xml ) in POM.xml

As Page object Model, Here in project directory ..src\main\java\pageObjects all page object java classes are present.

In the project directory ...\src\main\java\resources all resources like base(java class),data(properties file),ExtentReporterNG(java class),Log4j2(xml file)

In the project directory ....\src\test\java all cucumber BDD related files like CucumberOptions,features and StepDefinations are present.
