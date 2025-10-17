
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
```
https://charles-hng13-stage0-backend.pxxl.click/me
```

Platform: (https://pxxl.app/)


### Technical Stack  ###

Framework: FastAPI

Programming Language: Python 3

ASGI Server: Uvicorn

HTTP Client: HTTPX (for external API calls)

External API: Cat Facts API (https://catfact.ninja/fact)


### Instructions to run locally  ###

Follow the steps below to set up and run the application on your local machine.

✅ Prerequisites

Ensure Python 3 is installed on your machine.

Install and activate a virtual environment.
```
Python3 -m venv venv
source /venv/bin/activate
```
🔧 Setup Instructions

Clone the Repository
```
git clone git@github.com:Gitauwairimu/hng13-stage0-backend.git
```

Navigate to the Project Directory
```
cd fastapi-app
```

Install Dependencies
```
pip install -r requirements.txt
```

Configure Environment Variables

Open main.py and update the following variables with your personal details:
```
USER_EMAIL = "your email"
USER_NAME = "your full name"
USER_STACK = "your stack"
```

Run the Application
```
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

Access the Application
```
http://localhost:8000/me

```