# Simple-Flask-Blog-Project
A blog website project which uses flask micro web framework for backend and mysql for database...

*Python is a powerful general-purpose programming language. It is used in web development, data science, creating software prototypes, and so on. Fortunately for beginners, Python has simple easy-to-use syntax. This makes Python an excellent language to learn to program for beginners.

* Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions

* To run the application you can either use the flask command or python’s -m switch with Flask. Before you can do that you need to tell your terminal the application to work with by exporting the FLASK_APP environment variable:

$ export FLASK_APP=hello.py

$ flask run

 * Running on http://127.0.0.1:5000/
 
If you are on Windows, the environment variable syntax depends on command line interpreter. On Command Prompt:

C:\path\to\app>set FLASK_APP=hello.py

And on PowerShell:

PS C:\path\to\app> $env:FLASK_APP = "hello.py"

Alternatively you can use python -m flask:

$ export FLASK_APP=hello.py

$ python -m flask run

 * Running on http://127.0.0.1:5000/
 
 * If you have the debugger disabled or trust the users on your network, you can make the server publicly available simply by adding --host=0.0.0.0 to the command line:

$ flask run --host=0.0.0.0

*We Used the route() decorator to bind a function to a URL.

@app.route('/')

* We have defined various functions
* We have defined App also 

* To render a template we use the render_template() method
from flask import render_template

@app.route('/')

*We have Use Templates Inheritance for the ease 

*
APIs with JSON¶

A common response format when writing an API is JSON. It’s easy to get started writing such an API with Flask. If you return a dict from a view, it will be converted to a JSON response.
