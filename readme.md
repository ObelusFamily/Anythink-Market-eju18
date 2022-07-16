# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Docker client must be installed.   This is outside the scope of this document

To start the application run ```docker compose up```
The containers will require several minutes to build
Confirm the back end by visiting http://localhost:3000/api/ping
Confirm the front end by visiting  http://localhost:3001/register