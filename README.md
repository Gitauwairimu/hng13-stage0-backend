
# HNG Internship - Backend Track

## Backend Stage 0 Project Project Overview ##
A FastAPI backend application that provides a RESTful API endpoint returning user information along with random cat facts. This project demonstrates backend development skills with Python and FastAPI framework.


### Student Information ###
Name: Charles Gitau Wairimu

Slack Username: @Gitau Wairimu

Track: Backend

Stage: 0

##  Deployment Details ##

### Base URL ###

http://34.229.144.242:8000

Platform: AWS

### Technical Stack  ###

Framework: FastAPI

Programming Language: Python 3

ASGI Server: Uvicorn

HTTP Client: HTTPX (for external API calls)

External API: Cat Facts API (https://catfact.ninja/fact)


### Instructions to run locally  ###
Ensure your local machine has Python version 3
Install and activate a python environment
Clone the repository - git clone <repository-url>
Navigate to main code directory - cd fastapi-app
Install the dependencies - pip install -r requirements.txt
In the main.py, change the environment variables to reflect your details
USER_EMAIL = "your email"  
USER_NAME = "your full name"
USER_STACK = "your stack"

Run the application using - uvicorn main:app --host 0.0.0.0 --port 8000 --reload