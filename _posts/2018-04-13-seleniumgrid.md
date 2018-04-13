---
layout: post
title: Selenium Grid
---

![Selenium Grid]({{site.baseurl}}/images/seleniumgrid.png)


### Notes on Selenium Grid
##### 1. Selenium Grid is used to run automation scripts on different versions of browser, OS etc.
##### 2. Selenium grid will have one Hub(like a server) and multiple nodes.

##### 3.To run the scripts on VM's, remote webdriver(a Class) is used. Information is passed from local   machine to the Hub on the desired capabilities(OS,Browser,version).

##### 4. Communication from the hub to nodes happen via JSON wire/HTTP.

##### 5. RemoteWebDriver is an implementation class of the WebDriver interface that a test script developer can use to execute their test scripts via the RemoteWebDriver server on a remote machine.

##### 6.The desired capability is a series of key/value pairs that stores the browser properties like browsername, browser version, the path of the browser driver in the system, etc. to determine the behaviour of the browser at run time





### Configuring Selenium Grid:
##### 1. Download Selenium Standalone Server from Selenium HQ.
##### 2.Move it to a folder of your choice (D:\Pradeep\Selenium drivers in my case).
##### 3. Launch command prompt and run the java -jar selenium-server-standalone-3.11.0.jar    command."Selenium Grid hub is up and running" message should be displayed.

##### 4. Launch the browser and go to the URL mentioned in the command prompt.If it is being    launched in local machine, then go to http://localhost:portnumber.

##### 5.If it starts successfully,"Whoops! The URL specified routes to this help page." message   would be displayed in the browser.

##### 6. To register the Hub, open a new terminal and give the command - java -Dwebdriver.chrome.driver="D:\Pradeep\Selenium drivers\chromedriver.exe" -jar selenium-server-standalone-3.11.0.jar -role node -hub http://localhost:4444/grid/register.

##### 7. " The node is registered to the hub and ready to use" message should be displayed.

{% highlight css %}

