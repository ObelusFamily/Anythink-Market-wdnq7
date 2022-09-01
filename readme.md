# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

First step is to [install Docker](https://docs.docker.com/get-docker/)

Once you have docker installed start the frontend and backend with `docker-compose up`.

After the app is running, test that the backend is running and able to communicate with the db by visiting `http://localhost:3000/api/ping` in the browser.

Next check the frontend. If everything is working correctly, you will be able to register a new user at `http://localhost:3001/register`
