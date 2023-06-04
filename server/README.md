# NearbyFeed Backend

This is the backend server for the NearbyFeed app. It provides the necessary APIs and functionalities for creating, retrieving, and managing posts and comments in the NearbyFeed app.

## Installation

1. Clone this repository to your local machine.
2. Navigate to the project's root directory.
3. Run the following command to install the required dependencies:
```bash
$ yarn install
```

## Docker Setup
The NearbyFeed Backend uses Docker for containerization. To build the Docker containers with docker-compose, run the following command:
```bash
$ yarn dc:up
```

## Database setup
To set up the database, run the following commands:
```bash
$ yarn prisma:dev:migrate
$ yarn prisma:generate
```



## Running the app

```bash
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

## Test

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```
