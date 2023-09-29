Project title: Python Network Scripts
This project contains a collection of Python scripts for performing various network-related tasks. These scripts are designed to help you understand and work with network requests and APIs.

Scripts Overview
Task 0: 0-hbtn_status.py
What's my status?

Fetches data from https://alu-intranet.hbtn.io/status.
Displays the response body in a specific format.
Response header value

Task 1: 1-hbtn_header.py
Takes a URL as input.
Sends a request to the URL and displays the X-Request-Id value from the response header.
POST an email

Task 2: 2-post_email.py
Accepts a URL and an email address as input.
Sends a POST request to the URL with the email as a parameter.
Displays a message containing the provided email address.
Error code

Task 3: 4-error_code.py
Takes a URL as input.
Sends a request to the URL and displays the response body.
Prints an error message if the HTTP status code is >= 400.
Search API

Task 4: 5-json_api.py
Takes a letter as input.
Sends a POST request to http://0.0.0.0:5000/search_user with the letter as a parameter.
Displays user information or appropriate messages based on the input letter.
My GitHub!

Task 5: 6-my_github.py
Takes your GitHub username and personal access token as input.
Uses the GitHub API to display your GitHub user id.
Returns your user id or "None" if authentication fails.
Feel free to explore and use these scripts as needed. Instructions for running each script are provided in their respective sections within this repository.