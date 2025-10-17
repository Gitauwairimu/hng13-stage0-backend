
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

Clone the repository 
bash
git clone git@github.com:Gitauwairimu/hng13-stage0-backend.git

Navigate to main code directory - 
bash
cd fastapi-app

Install the dependencies - 
bash
pip install -r requirements.txt

In the main.py, change the environment variables to reflect your details
bash
USER_EMAIL = "your email"  
USER_NAME = "your full name"
USER_STACK = "your stack"

Run the application using: 
bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload






Instructions to Run Locally
Prerequisites
Ensure your local machine has Python version 3.7 or higher installed.

Step-by-Step Setup
Install and activate a Python virtual environment

bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
# On Linux/Mac:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
Clone the repository

bash
git clone git@github.com:Gitauwairimu/hng13-stage0-backend.git
Navigate to the main code directory

bash
cd hng13-stage0-backend/fastapi-app
Install the dependencies

bash
pip install -r requirements.txt
Configure your personal details

Open main.py in a text editor

Update the following environment variables with your information:

python
USER_EMAIL = "your_email@example.com"  # Replace with your email
USER_NAME = "Your Full Name"           # Replace with your full name
USER_STACK = "Your Backend Stack"      # Replace with your stack (e.g., "Python/FastAPI", "Node.js/Express")
Run the application

bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
Verify the Application is Running
Access the API endpoint in your browser or via curl:

text
http://localhost:8000/me
You should see a JSON response like:

json
{
  "status": "success",
  "user": {
    "user.email": "your_email@example.com",
    "user.name": "Your Full Name",
    "user.stack": "Your Backend Stack"
  },
  "timestamp": "2024-10-15T14:30:45.123Z",
  "fact": "A random cat fact will appear here"
}