**** Instruction to run the project **** 1. Unzip the download file 2. Now you will get the project folder, its a Maven project 3. You can open Maven project directly using any IDE like Eclipse or intellij. (I have used intellij to create my project) 4. Then open the project, just click on the Run button to run the project.

**** Project Description ****

Have created a Maven project because it provides a folder structure src-->main -->test
Have used scripting language 'Java' and 'Junit' (unit test framework) because it supports Cucumber

Have created a Page object model where in 'main' folder, I have created separate classes for each webpage like Homepage, RegistrationPage

For all the actions that we need to perform on each webpage, have created separate methods for those actions in respected class. For example: in RegistrationPage class, I have created methods like RegistrationByEmail(arguments), verifyErrorMessage(errormsg)

BrowserFactory class : to create and to get the instance for browser class

Utils class : Utils class is for reusable component which have all the methods those are not related to application

Inside 'test' folder I have created 'Resources' directory that have feature files

Now in 'test' folder I have created the RunTest class : that is cucumber Runner class Stepdefs class : contains all the step definitions, methods for all feature file scenarios
