# MongoDB Container

This project contains a docker compose file to build MongoDB in a Docker container.

## Project Structure

```shell
.
├── .env
├── README.md
└── docker-compose.yaml
```

## Install

Change the default username and password in the .env file

```shell
MONGO_DB_ROOT_USER=root
MONGO_DB_ROOT_PW=rootpassword
```

Run the following command to pull and run the image

```shell
docker compose up -d
```

## User Interface

Install MongoDB Compass for a GUI interface
[MongoDB Compass](https://www.mongodb.com/docs/compass/current/)
