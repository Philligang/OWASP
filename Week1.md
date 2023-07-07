

# Week 1 Flex

This is the progress we made in our first week in the OWASP Juice Shop.

### Part I - Acquiring BURP Suite
We downloaded the BURP suite from https://portswigger.net/burp and then applied it to our VM through the command line and acquainted ourselves with the basic functions and uses.


### Part II - Challenge Completion
We completed 2 one star challenges, 2 three star challenges, and 2 five star challenges.

### Part III - Hardening
First and foremost the client side has WAYYYYY to much access to the functions and data related to users. Swapping some of the data manipulation to a server side, that would add a layer of protection.

Beyond that, for accessing admin only portions of the site, make them password protected. Not simply a hidden index.

An issue we spotted was that when checking password, it only checks once. so you can input the repeated password for verification then backtrack and put whatever password your heart desires. In order to fix this, the function that verifies the passwords authenticity should run whenever the original or repeated password is changed.

When changing passwords to log into their accounts, their login info was available online. Be sure to train employees in safe security practices. 

While injecting files that are not expected, create a secondary check on file size and type to ensure they haven't been falsified between submission and reception.





