# SeleniumPageObjectModelFrameWork
Create a framework with all concepts of Selenium with Java

1. Implemented Core principles of Selenium UI Automation Project 

2. Made sure The following principles/Methods immplemented removing general Bad practices
  Non Atomic Tests , code Duplication
    Duplicate Element Definitions--> page object model
    Duplicate test steps -->discrete tests
    User and Application State Dependencies --> Create state
    Poor readability -> Page Object Model, Good method names
    Driver Initialization duplicate code --> TestNG annotations
    Thread.sleep -> Explicit Waits
    Non Readable Tests - implemented atomic tests single responsibility methods 
    Duplicate Driver Initialization code -- Base test and driver manager using OOPS concepts 
    Static sleeps (Thread.sleep()) -->Explicit Waits 
    Hardcoded Test Data -- > Constants \Enums
    Hardcoded Static Text --> XML's
    Lacking Multiple Browser Support -->system Parameters
    Hardcoded Driver Executable Path and Manual Driver Management -- >auto Discovery config properties
    Stale Browser 
    Stale Instances when failure
    multiple Environment, Multi browser support - using Maven command line as well as Textng xml
    PageFactory concept
   API reassured , JSON , HTML automation concept
   Singleton design Pattern - Config properties
   Factory Design pattern
   Extent reports , allure reports
   TestNG data provider
   Excel test data , results in exce reports
   Screenshots on failure -->after method ITResult failure 


Readable,Maintainable and Scalable
DRY - Do not Repeat Yourself
SRP - Single Responsibility Principle
OOP - Encapsulation, Inheritance and Interface and Polymorphism.
