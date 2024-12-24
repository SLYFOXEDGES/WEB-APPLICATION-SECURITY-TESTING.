#GEO STALKING-VISUALIZATION
 Geo-stalking refers to tracking someone's location using geographic data, typically through digital means like GPS, social media check-ins, or mobile device location services. This practice can have serious privacy and security implications.

Here are the steps to complete the "GEO Stalking" challenge in Juice Shop:

Step 1: Find the Vulnerable Endpoint

1. Open Juice Shop in your browser.
2. Use Burp Suite or your browser's developer tools to analyze the HTTP requests.
3. Find the endpoint that handles user location updates (e.g., /api/locations).

Step 2: Identify the Vulnerable Parameter

1. Analyze the request body or parameters of the location update endpoint.
2. Identify the parameter that contains the user's location coordinates (e.g., latitude and longitude).

Step 3: Craft a Malicious Request

1. Use Burp Suite or a tool like curl to craft a malicious request.
2. Modify the location coordinates to a fake value.
3. Send the request to the vulnerable endpoint.

Step 4: Visualize the Stalking

1. Open the Juice Shop map view.
2. Observe how the user's location marker has been updated to the fake coordinates.
3. Congratulations, you have successfully demonstrated GEO stalking!

Additional Tips

- Make sure to use a proxy or intercepting tool to analyze and modify the HTTP requests.
- Be cautious when testing this vulnerability, as it may affect the Juice Shop's functionality or other users' experiences.
- This challenge is meant to demonstrate the risks of inadequate input validation and insecure handling of user location data.
