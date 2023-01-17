# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## How to run locally?
1. [Install Docker](https://docs.docker.com/get-docker/)
2. [Install Docker Compose](https://docs.docker.com/compose/install/)
3. Run `docker-compose up`. 

If Docker is working correctly, the backend should be running and able to connect to your local database. Test this by pointing your browser to http://localhost:3000/api/ping

To check the frontend and make sure it’s connected to the backend, you’ll be able to create a new user on http://localhost:3001/register. 
Create one (choose a cool nickname and everything).
