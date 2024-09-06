# Docker Node Starter
A simple starting point for Node.js containers.

## Getting started
Create an `.env` file and set the `APP_NAME`
```sh
cp .env.dist .env.local
```

```sh
APP_NAME=docker-node-starter
```

Build the image and start the container
```sh
docker compose up --build -d
```