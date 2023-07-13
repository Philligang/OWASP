

# Week 2 Flex

This is the progress we made in our second week in the OWASP Juice Shop.

### Part I - Summary of Exploits

The primary challenges we completed were Bully Chatbot, Kill Chatbot, CAPTCHA Bypass, Zero Star review, and we retrieved the Extra Language.

### Part II - Challenge Completion

We completed 2 one star challenges, 2 three star challenges, and 2 five star challenges.

### Part III - Hardening

First of all when programming a chatbot, don't give it the power to give out discount codes, what happened to the principle of least privilege?

For the Kill Chatbot challenge, the chat feature takes user input directly before sanitizing it allowing users to inject malicious code directly to the chatbot. Maybe add a layer that will sanitize the input before applying.

In CAPTCHA bypass and the zero star review, packets can be intercepted and modified before reaching the server. This could be resolved by adding a check on the server side to compare to the initial user input. Also we'd recommend limiting the number of reviews that a single account can make in a period of time to mitigate the possibility of fraudulent reviews.







