## Project Object Model

1. POM is used for adding project dependencies. It comes as part of the Maven project setup.
2. SRC is the source folder. SRC Test java folder will contain only test cases. SRC main java folder will contain utilities,page classes,libraries etc.

3. Create individual package for each section(Example: Test data,Utilities,Base, config).

4. For reports, folder is created automatically.

5. Define common properties within the config package by creating a new file. Specifiy the URL,username and password and Browser details.

6. Inside the "Page" package, create all the pages.(Example: Login page,signup page,homepage)

##

TestBase.java

Testbase.java file will be the base class for all the other java class files.This class will contain the details of the configuration file, code related to window maximization and code related to launching the URL.