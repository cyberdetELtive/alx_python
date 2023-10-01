Project README
This README provides an overview of the Flask web applications created as part of the ALX Python Web Framework project. Each application is a Python script that starts a Flask web server with specific routes and functionalities.

Table of Contents
Hello Flask
HBNB
C is Fun
Python is Cool
Is it a Number
Number Template
Odd or Even

Hello Flask
Description
This Flask application listens on 0.0.0.0, port 5000.
It has a single route / which displays "Hello HBNB!" when accessed.
The strict_slashes=False option is used in the route definition.

HBNB
Description
This Flask application is an extension of the Hello Flask app.
It still listens on 0.0.0.0, port 5000.
It has two routes:
/ which displays "Hello HBNB!"
/hbnb which displays "HBNB"
The strict_slashes=False option is used in the route definitions.

C is Fun
Description
This Flask application is an extension of the HBNB app.
It still listens on 0.0.0.0, port 5000.
It has three routes:
/ which displays "Hello HBNB!"
/hbnb which displays "HBNB"
/c/<text> which displays "C " followed by the value of the text variable (underscores _ replaced with spaces).
The strict_slashes=False option is used in the route definitions.

Python is Cool
Description
This Flask application is an extension of the C is Fun app.
It still listens on 0.0.0.0, port 5000.
It has four routes:
/ which displays "Hello HBNB!"
/hbnb which displays "HBNB"
/c/<text> which displays "C " followed by the value of the text variable (underscores _ replaced with spaces).
/python/<text> which displays "Python " followed by the value of the text variable (underscores _ replaced with spaces).
The default value of text is "is cool".
The strict_slashes=False option is used in the route definitions.

Is it a Number
Description
This Flask application is an extension of the Python is Cool app.
It still listens on 0.0.0.0, port 5000.
It has five routes:
/ which displays "Hello HBNB!"
/hbnb which displays "HBNB"
/c/<text> which displays "C " followed by the value of the text variable (underscores _ replaced with spaces).
/python/<text> which displays "Python " followed by the value of the text variable (underscores _ replaced with spaces).
/number/<n> which displays "n is a number" only if n is an integer.
The default value of text is "is cool".
The strict_slashes=False option is used in the route definitions.

Number Template
Description
This Flask application is an extension of the Is it a Number app.
It still listens on 0.0.0.0, port 5000.
It has six routes:
/ which displays "Hello HBNB!"
/hbnb which displays "HBNB"
/c/<text> which displays "C " followed by the value of the text variable (underscores _ replaced with spaces).
/python/<text> which displays "Python " followed by the value of the text variable (underscores _ replaced with spaces).
/number/<n> which displays "n is a number" only if n is an integer.
/number_template/<n> which displays an HTML page only if n is an integer with an H1 tag: "Number: n" inside the tag BODY.
The strict_slashes=False option is used in the route definitions.

Odd or Even
Description
This Flask application is an extension of the Number Template app.
It still listens on 0.0.0.0, port 5000.
It has seven routes:
/ which displays "Hello HBNB!"
/hbnb which displays "HBNB"
/c/<text> which displays "C " followed by the value of the text variable (underscores _ replaced with spaces).
/python/<text> which displays "Python " followed by the value of the text variable (underscores _ replaced with spaces).
/number/<n> which displays "n is a number" only if n is an integer.
/number_template/<n> which displays an HTML page only if n is an integer with an H1 tag: "Number: n" inside the tag BODY.
/number_odd_or_even/<n> which displays an HTML page only if n is an integer with an H1 tag: "Number: n is even|odd" inside the tag BODY.
The strict_slashes=False option is used in the route definitions.

These Flask applications demonstrate the use of routes, route parameters, and HTML templates.