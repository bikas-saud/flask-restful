# Flask-RESTful

[![Build Status](https://travis-ci.org/flask-restful/flask-restful.svg?branch=master)](http://travis-ci.org/flask-restful/flask-restful)
[![Coverage Status](http://img.shields.io/coveralls/flask-restful/flask-restful/master.svg)](https://coveralls.io/r/flask-restful/flask-restful)
[![PyPI Version](http://img.shields.io/pypi/v/Flask-RESTful.svg)](https://pypi.python.org/pypi/Flask-RESTful)

Flask-RESTful provides the building blocks for creating a great REST API.

## User Guide

You'll find the user guide and all documentation [here](https://flask-restful.readthedocs.io/)

Flask resources include tutorials and tools, such as [Awesome Flask](https://github.com/mjhea0/awesome-flask)
## Main Steps 
### 1.
```
pip install flask
```
### 2. 
```
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, Flask!"

if __name__ == "__main__":
    app.run(debug=True)
```

