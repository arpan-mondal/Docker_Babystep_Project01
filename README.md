# Docker_Babystep_Project01

## Step 1 
Create a requirement.txt file

## Step 2 
Create a basic python file (write a basic python code) or you can use this resource 
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "<p>Hello, World!</p>"
