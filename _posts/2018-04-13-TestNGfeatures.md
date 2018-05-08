---
published: true
future: true
---
### Test NG features/options

## @Parameters in TestNG

Username,password,urls can be defined either in config.properties or within the TestNG file

1. Create testNG.xml file

### Format:
<suite name =  "Test suite">
<test name = "test cases">
<parameter name="url" value="https://freecrm.com">
<parameter name="email" value="pradepbhat@gmail.com">
<classes>
  <class name ="path.classname">
</classes> 
</test>
</suite>
  
  In the test case, parameter tag should be given along with @Testcase tag:
  
  @Test
  @Parameters("url", "emailid")
  Public void Loginpage(String url, String emailid){
  }

### Data driven approach can be done using the below resources:
   1. Excel sheet - Test data
   2. config.properties file - environment variables,Object repos, test data
   3. TestNG.xml - environment variables.
   4. XML file
   5.JSON files
   6. DB

## dependsOnMethods

@Test
public void loginTest(){

System.out.println("Welcome");

}

@Test(dependsOnMethods="loginTest") // will be executed only if loginTest is executed.

Public void loginagain(){

System.out.println("back");

}

## Groups tag

Groups tag is used to group the test cases under one set.

@Test( groups = "bus")

## invocation count

@Test(invocation count=10) //To execute same test case multiple times

Public void loginagain(){

System.out.println("back");

## timeout

@Test(timeOut=20000) // Will terminate the test case if it doesn't execute the test case within 20 seconds

Public void loginagain(){

System.out.println("back");

## Assertions

Assert.assertequals

Assert.assertTrue



