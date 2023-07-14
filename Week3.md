

# Week 3 Flex

This is the progress we made in our third week in the OWASP Juice Shop.

### Part I - Summary of Exploits

This week the exploits we completed entail, Changing admin Bjoern's passwords on both his accounts, we created a new admin level accout, We also stole the blueprint for sensitive product information.

### Part II - Challenge Completion

We completed 2 one star challenges, 2 three star challenges, and 2 five star challenges.

### Part III - Hardening

For Bjeorn's passwords on both accounts, the answers to his security questions were readily available on his social media. So you should train your admins on typical OSINT practices and defenses to ensure they keep potentially sensitive information in a more private setting.

When it came to creating a new admin account, it was another case of intercepting the packets after the check, but before they hit server-side, and then it was a simple matter of inserting a 15 character line of code setting the new user as an admin.

When stealing sensitive product blueprints, The blueprint was saved in the public HTML with the product images. In order to prevent this from happening in the future, save private info not on the public facing webapp.
