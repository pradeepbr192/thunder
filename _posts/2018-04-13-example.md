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





## Paragraphs

These are sample paragraphs showing *italics*, **bold** and ``code`` text style. Here is an unordered  list 

* Item 1
* Item 2
* Item 3

and an ordered list

1. Item 1
2. Item 2
3. Item 3

>A blockquote would look like this.

> another one 
>
> with multiple lines




Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

**Code:** Let's keep it to its length and let it not take the whole width.
{% highlight html %}

<div class="nav">
    <ul>
        <li>About</li>
        <li>Contact</li>
        <li>Project</li>
    </ul>
</div>


{% endhighlight %}

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit.

This is a simple markdown table

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |



Use below code to show **Table of Contents** on a page

{% highlight css %}
* Do not remove this line (it will not be displayed) 
{:toc}
{% endhighlight %}
