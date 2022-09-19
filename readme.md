# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Goto the root folder of the project and type the command - `docker compose up`
2. This command executes the `docker-compose.yml` file and deploys the code in the local environment
3. Use the url to test the backend - `http://localhost:3000/ping`
4. Use the url to test the frontend - `http://localhost:3001/register`
