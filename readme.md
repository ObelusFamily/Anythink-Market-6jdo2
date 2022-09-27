# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Make sure to have Docker installed on your machine and the docker engine up and running. 
Installation can be confirmed with "docker -v" and  "docker-compose -v"

Clone Project from Github
Run "docker-compose -up" in project root directory
wait for docker images to build and run

to check backend, navigate to http://localhost:3000/api/ping

to check frontend, navigate to http://localhost:3001/register
