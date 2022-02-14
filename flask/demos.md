## Flask
Flask is a lightweight framework that gives abundant features without external libraries and minimalist features.

#### Features
Development server and debugger.
Integrated support for unit testing.
RESTful request dispatching.
Uses Jinja templating.
Support for secure cookies (client side sessions)


### Demo Application
<pre>
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "<p>Hello, World!</p>"
</pre>

where 
  - app is the instance of Flask class that we imported<br/>
  - @app.route() a decorator which tells falsk at which URL the function gets executed <br/>

**To run the application** we need to save that file with .py extention and set the environmental variable as follows.<br/>
<pre>
 >set FLASK_APP = file_name.py
 >flask run
</pre> 
Our application runs on the ip*127.0.0.1:5000*
