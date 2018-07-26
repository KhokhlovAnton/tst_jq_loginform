# tst_jq_loginform

Specification: 
1.	The border will be centralized on the page.
2.	Create a JSON file that contains at least 3 users, each user will have the following fields: UserName, Password, FirstName & LastName  with random values, you may add fields to this file if needed, one of the users will be Username: Test, Password: 1234.
3.	Upon Log in button click – use Ajax action on Jquery ($.ajax) that performs username and password validation.
4.	If validation succeeds – the Log in button will disappear, and a message in green -“welcome XXX” (name of the user) will appear.
5.	If validation failed – a message will appear in red - “looks like one of the fields is incorrect, please try again.”
6.	After 3 failed attempts – move to fail page (404). 
7.	Username field will include only letters.
8.	Password field will include only numbers.
HighLights:
•	Username: Test, Password: 1234 – check if exists on server side with Json File.
•	Use pure CSS – in a separate CSS page, not inline style.
•	Don’t use Table tags.
