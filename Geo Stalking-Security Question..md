#Geo Stalking-Security Question.
![image](https://github.com/user-attachments/assets/12697e21-36aa-420c-bb8f-53c1948955e3)
Security questions are commonly used as an additional layer of protection during the password recovery process. Here are some frequently asked security questions:
What is your mother's maiden name?
What was the name of your first pet?
What is the name of the street you grew up on?
What was the name of your elementary school?
What is your favorite book?
What was the make and model of your first car?
What is your favorite movie?
What is your father's middle name?
What was your childhood nickname?
In what city were you born?



1 Question
What is the favorite hiking spot of the user with the email address "admin@juice-sh.op"?

Solution
1. Open Burp Suite and configure it to intercept traffic from your browser.
2. Log in to Juice Shop as the admin user.
3. Go to the "My Account" page and click on the "Edit" button.
4. In Burp Suite, intercept the request to update the user's profile.
5. Modify the request to include a new favorite hiking spot (e.g., "Mount Everest").
6. Forward the modified request to the server.
7. Go back to the "My Account" page and verify that the favorite hiking spot has been updated.
8. Now, use the "Forgot Password" feature to reset the admin user's password.
9. In the password reset email, you'll find a link to reset the password.
10. In Burp Suite, intercept the request to reset the password.
11. Modify the request to include the correct answer to the security question (i.e., the favorite hiking spot).
12. Forward the modified request to the server.
13. Verify that the password has been successfully reset.

Correct Answer
The correct answer to the security question is the favorite hiking spot you specified earlier (e.g., "Mount Everest").

The "Geo Stalking" challenge in Juice Shop involves finding the answer to a security question related to Kentucky.

2 Question
What is the name of the Kentucky park where the admin user went hiking?

Solution
1. Use Burp Suite or your browser's developer tools to analyze the HTTP requests.
2. Find the request that contains the admin user's location data.
3. Analyze the request parameters or body to find the name of the Kentucky park.

Correct Answer
The correct answer to the security question is "Red River Gorge

