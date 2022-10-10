# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone this repo
2. From project root, run `docker-compose up`
3. Confirm backend is running by visiting `http://localhost:3000/api/ping`
4. Confirm frontend is running at `http://localhost:3001/register`
5. Register new username via frontend

Note: use `docker exec` to run commands on a container
