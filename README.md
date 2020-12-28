# bluesky-users
Testing using FastAPI Users in bluesky-webclient.
[bluesky-webclient](https://github.com/bluesky/bluesky-webclient)

<hr>

## Acknowledgement
- Thank you [ankushjain2001](https://github.com/ankushjain2001) for the very nice template repo.
- The backend authentication is built using [franke567's](https://github.com/frankie567) [fastapi-users](https://github.com/frankie567/fastapi-users) python package for FastAPI. It provides easy out-of-the-box backend auth components.

<hr>

#### Swagger UI API Documentation
![Swagger UI API Documentation](https://user-images.githubusercontent.com/10784445/93062570-bd23d680-f63a-11ea-8d6a-2a2d121817a4.png)

<hr>

## Setup Instructions
#### A. MongoDB Database
1. Install [MongoDB-4.4.0](https://docs.mongodb.com/manual/installation/)

#### B. Dependancies
```bash
pip install -r requirements.txt
```

## Run Instructions
#### A. MongoDB Database
- Start MongoDB server
#### B. Python/FastAPI Backend
```bash
uvicorn main:app --port=9000
```
