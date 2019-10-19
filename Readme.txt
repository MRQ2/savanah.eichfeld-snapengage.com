snapengage-qa.appspot.com
Conceptual Assessment of Automation

Following is the definition of in which classes the task are solved.

Open Chrome browser 
Solution: src/main/java/com/cucumberFramework/stepdefinitions/Hooks.java

Go to https://snapengage-qa.appspot.com/signin?to=hub 
Solution: /src/test/resources/features/Login.feature

Type Username: pedroalmodovar@test.com 
Solution: /src/main/java/com/cucumberFramework/stepdefinitions/LoginPageStepDefinitions.java

Type Password: 1q2w3e 
Solution: /src/main/java/com/cucumberFramework/stepdefinitions/LoginPageStepDefinitions.java

Click Sign In button 
Solution: /src/main/java/com/cucumberFramework/stepdefinitions/LoginPageStepDefinitions.java

Assert that Hub (our agent portal) is loaded 
Solution: /src/main/java/com/cucumberFramework/stepdefinitions/LoginPageStepDefinitions.java

Take a screenshot 
Solution: /src/main/java/com/cucumberFramework/stepdefinitions/LoginPageStepDefinitions.java Screenshot is saved main hierarchy, Please refresh the project after successful run

Tear down Chrome browser 
Solution: /src/main/java/com/cucumberFramework/stepdefinitions/LoginPageStepDefinitions.java

Extra: LoggerHelper Class is created for making logs 
WaitHelper Class is created for element visibility 
Testbase Class is created for handling webdrivers 
TestRunner Class is created for TestNG execution and Cucumber Options Configurations Homepage Class and its Page Object is created from dummy purpose

Notebell: My own project is also in the repository but due to errors its need fixing. For your task, I just changed the basic archietecture of my work to give a generic idea of how should a project should look like.

HOW TO RUN THE PROJECT 
Steps to reproduce: 
Download zip file from the repository 
Unzip in desired folder 
Open Eclipse Navigate to workbench mode 
Click on button "File" and select option "Open Projects from file system" 
In popup window, click on button "Director" and Select folder of downloaded repository 
Click button "Finish" 
Trickle down folder "TestRun" 
Navigate to "POM.xml" file, open it by double clicking 
Right click inside the file and select option "Run" -> "Maven install"

OR 

Navigate to file "/src/main/java/com/cucumberFramework/testRunner/TestRunner.java"
Right click inside the file and select option "Run As" -> "TestNG Suite"
