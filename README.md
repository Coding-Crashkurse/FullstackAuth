# Fullstack Auth

This repository shows a secure way to authenticate with httpOnly cookies in FASTApi.
The frontend provides a few buttons and textinputs to register a new user, login and access data which from the procted `/api/protected` endpoint.

## Use this app:

Run `docker-compose up --build`

The FastAPI app will fail multiple times at first startup, since it depends on the MySQL Container, which takes a few seconds to start and setup a new Database the first time. No worry, this is handled by restarting the app until the MySQL Container is up and running
