# Docker Python Demo

Simple Python Flask application running inside Docker.

## Run Locally

Build image

```
docker build -t docker-python-app .
```

Run container

```
docker run -p 5000:5000 docker-python-app
```

Open browser

```
http://localhost:5000
```

## Project Structure

```
project
│
├── app.py
├── requirements.txt
├── Dockerfile
```

## Tech Stack

Python  
Flask  
Docker
