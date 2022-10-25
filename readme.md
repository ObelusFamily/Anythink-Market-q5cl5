# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
### 1. Clone reporosity
``` cmd
git clone https://github.com/ObelusFamily/Anythink-Market-q5cl5.git
```

### 2. [Get Docker](https://docs.docker.com/get-docker/)

### 3. Stop mongodb if it is being used
``` cmd
sudo service mongod status
sudo service mongod stop
```

### 4. Docker up
``` cmd
docker compose up
```

### 5. Test by [visiting ping](http://localhost:3000/api/ping)

### 6. [Create a new user](http://localhost:3001/register)
