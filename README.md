# SeleniumFwork
Step 1: Creating a maven project
--------
Create a Maven Project--> File --> New Maven --> Maven Project --> Next --> Select an ArcheType "Group ID: org.apache.maven.archetypes", Artifact Id: maven-archetype-quickstart"
This will create 2 packages under src/main/java and src/test/java, delete these packages
Create our own packages under src/test/java: 1) com.nopcommerce.pageObjects 2)com.nopcommerce.testBase 3)com.nopcommerce.testCases 4) com.nopcommerce.Utilities

Step 2: Creating Folder Structure
--------
Create own folders 1)Configurations 2)Logs 3)Reports 4)Screenshots 5)testData 6)target
By default maven project will create a pom.xml file where we have to install all the dependencies

Once all the dependencies are added save the POM.xml and RC on the root of Maven project folder, Go to Maven --> Update Project

Create a Page object Java file which will have the page webelements information and methods to login and perform actions on the page in this file
src/test/java: 1) com.nopcommerce.pageObjects --> EX: LoginPage.java

Step 3: Writing Login Test Case
--------

Create a Test case Java file "TC_LoginTest_001.java" which will have the instantiate the LoginPage constructor and use the WebElements from the LoginPage.java file 
src/test/java: 1) com.nopcommerce.testCases

