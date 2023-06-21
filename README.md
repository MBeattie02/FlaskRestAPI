# FlaskRestAPI

> Simple Python and Flask REST API

## Features and Technologies 

 - Python
 - Flask
 - SQLAlchemy
 - Docker


## End Points
<img width="831" alt="Screenshot 2023-06-20 at 15 24 28" src="https://github.com/MBeattie02/FlaskRestAPI/assets/91721899/b288cac4-288e-4375-8653-bf2b7527f02c">

## Useful Commands

 - python3 -m venv .venv
 - docker build . -t python-rest
 - docker run -dp 5000:5000 -w /app -v "$(pwd):/app" python-rest

## Docker 

 - [👉Docker Hub 🐳](https://hub.docker.com/r/mabeatti/flask-rest-api) 
 - Query in Postman
 - use http://127.0.0.1:8000/swagger-ui to get detailed explanation of all endpoints

 - Docker commands

 - docker build . -t flask-rest-api
 - docker tag flask-rest-api mabeatti/flask-rest-api
 - docker run --rm -it -p 8080:5000 mabeatti/flask-rest-api
 - docker pull mabeatti/flask-rest-api:latest
