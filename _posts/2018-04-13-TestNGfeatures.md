---
published: true
future: true
---
### Test NG features/options

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



