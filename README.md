# Flask-Notes-App

This is a simple Flask app that allows users to create, view, update, delete, share notes. It also allows to query notes based on keywords.
It implements jwt based authentication for using any APIs. It also implements basic rate limiting and api throttling to handle high traffic.

## Database Used
  MySQL

## Framework
  Flask

## Setup 
1. Clone the repository:
   git clone https://github.com/pasati072020/Flask-Notes-App.git

2. Install the requirements
   pip3 install requirements.txt

3. Add database configuration details in environment variables. It is used in file app_conf.py.

4. Run the App Locally
   python3 main.py --> This will start the app locally on the system and create the necessary database and tables on MYSQL.

5. In order to test the API, use the endpoint "/api/auth/signup" by providing username and password as payload. This will register user in the database.
   Next, use the endpoint login to get the auth token.

6. Auth Token needs to passed to all the APIs in order to get the correct response.
