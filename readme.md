# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

> Please make sure Docker is installed on your machine

1. Start the app by running `docker-compose up`
2. Make sure the backend is running and able to connect to your local database by pointing your browser to `http://localhost:3000/api/ping`
3. Once you receive that confirmation, you can validate that the frontend can connect to the backend properly by creating a new user at `http://localhost:3001/register`.
