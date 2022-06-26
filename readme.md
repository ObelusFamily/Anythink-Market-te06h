# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

### Step 1:

Make sure you have docker installed in your system, which you can then check by running the command `docker -v` and `docker-compose -v`

### Step 2:

Then go ahead and clone the repo to your system and then go to the repo's root directory and run the command `docker-compose up`

To check whether it worked you can first ping your browser to (http://localhost:3000/api/ping) and then to ensure that the backend part is connected to the frontend you can check it here (http://localhost:3001/register).
